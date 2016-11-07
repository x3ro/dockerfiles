FROM codenvy/ubuntu_rails

RUN echo "export PATH=\"/usr/local/bundle/bin:$PATH\"" >> /home/user/.bashrc

ADD Gemfile /gemfiles/Gemfile
ADD Gemfile.lock /gemfiles/Gemfile.lock

RUN cd /gemfiles && bundle
