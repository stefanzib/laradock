FROM gitlab/gitlab-ce:latest

RUN curl -sSL https://get.docker.com/ | sh \
    && curl -L https://packages.gitlab.com/install/repositories/runner/gitlab-runner/script.deb.sh | bash \
    && apt-get install gitlab-runner

EXPOSE 80 443