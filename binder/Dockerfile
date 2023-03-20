FROM rubydata/minimal-notebook:3d2a68af5c1f
ENV TAG=3d2a68af5c1f

RUN gem update \
      red_arrow\
      red_amber\
      red-datasets\
      red-datasets-arrow\
      red-arrow-numo-narray\
      rover-df

ADD binder/*.ipynb ./
