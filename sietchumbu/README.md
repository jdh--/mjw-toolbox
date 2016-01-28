# ikev2 CA & certificate creation

## CA
    # doas ikectl ca sietchumbu create
    # doas ikectl ca sietchumbu install

## server
    # doas ikectl ca sietchumbu certificate 96.88.251.140 create server
    # doas ikectl ca sietchumbu certificate 96.88.251.140 install

## client
    # doas ikectl ca sietchumbu certificate shadeout.nodeless.net create client
    # doas ikectl ca sietchumbu certificate shadeout.nodeless.net install
    # doas ikectl ca sietchumbu certificate shadeout.nodeless.net export
