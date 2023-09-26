FROM ubuntu
RUN sudo apt update && sudo apt install ffmpeg -y && sudo apt install -y python3-pip

RUN sudo pip install -U openai-whisper

RUN sudo pip install setuptools-rust

ENTRYPOINT ["bash"]