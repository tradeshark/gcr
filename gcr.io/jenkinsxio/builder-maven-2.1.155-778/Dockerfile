FROM gcr.io/jenkinsxio/builder-maven:2.1.155-778
ENV HOME /tekton/home
RUN touch /tekton/home/.gitconfig && git config --global url."https://hub.fastgit.org".insteadOf https://github.com
RUN echo ${HOME}/.gitconfig
