# Install jekyll (and rdiscount and pygments)
#

FROM sujaymansingh/python2.7
MAINTAINER Sujay Mansingh

RUN apt-get install -y rubygems

RUN gem install rdoc
RUN gem install json
RUN gem install rdiscount

RUN pip install pygments

RUN gem install jekyll

