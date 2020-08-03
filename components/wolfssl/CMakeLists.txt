set(srcs 
    src/bio.c
    src/crl.c
    src/internal.c
    src/keys.c
    src/ocsp.c
    src/sniffer.c
    src/ssl.c
    src/tls.c
    src/tls13.c)
set(include_dirs include wolfssl wolfssl/wolfcrypt)
idf_component_register(SRCS "${srcs}"
            INCLUDE_DIRS "${include_dirs}")