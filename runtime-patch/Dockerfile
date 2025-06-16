# 1. Comece com a imagem oficial do runtime, que sabemos que tem o problema
FROM docker.all-hands.dev/all-hands-ai/runtime:0.41-nikolaik

# 2. Copie nosso arquivo modificado por cima do original dentro da imagem.
#    O caminho de destino (/openhands/code/...) foi retirado dos logs de erro do runtime que vimos antes.
COPY ./openhands/utils/async_utils.py /openhands/code/openhands/utils/async_utils.py