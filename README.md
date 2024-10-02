Start Server:
python Server.py server_port (choose a server port over 1024)

Example:
python Server.py 5555

Start Client:
python ClientLauncher.py server_host server_port RTP_port video_file
Substitua:
server_host -> pelo endereço do servidor (localhost, por exemplo)
server_port -> pela porta do servidor
RTP_port    -> pela porta para receber pacotes RTP. 
video_file  -> Use o arquivo de vídeo fornecido (movie.Mjpeg).

Exemplo:
python ClientLauncher.py 127.0.0.1 5555 6000 movie.Mjpeg"# redes-2-rtsp-rtp" 
