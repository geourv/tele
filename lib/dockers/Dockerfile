FROM rocker/geospatial:4.0.2

# Bookdown
RUN install2.r --error --repos 'https://cran.rstudio.com/' \
	bookdown \
	tinytex \
	pander \
	kableExtra
	
# Better plots
RUN install2.r --error --repos 'https://cran.rstudio.com/' \
	cowplot \
	patchwork \
	ggrepel
	
# Diagrams
RUN install2.r --error --repos 'https://cran.rstudio.com/' \
	DiagrammeR \
	webshot
	
# Stats
RUN install2.r --error --repos 'https://cran.rstudio.com/' \
	corrplot


# Install all TeX and LaTeX dependences
# verify latex version
#RUN latex --version

# verify tlmgr version
#RUN tlmgr --version

# install texlive necessary packages
RUN tlmgr install \
  latex-amsmath-dev \
  iftex \
  euenc \
  fontspec \
  tipa \
  unicode-math \
  xunicode \
  kvoptions \
  ltxcmds \
  kvsetkeys \
  etoolbox \
  xcolor \
  auxhook \
  bigintcalc \
  bitset \
  etexcmds \
  gettitlestring \
  hycolor \
  hyperref \
  intcalc \
  kvdefinekeys \
  letltxmacro \
  pdfescape \
  refcount \
  rerunfilecheck \
  stringenc \
  uniquecounter \
  zapfding \
  pdftexcmds \
  infwarerr \
  fancyvrb \
  framed \
  booktabs \
  mdwtools \
  grffile \
  filehook \
  makecmds \
  polyglossia \
  natbib \
  multirow \
  wrapfig \
  float \
  colortbl \
  pdflscape \
  tabu \
  varwidth \
  threeparttable \
  threeparttablex \
  environ \
  trimspaces \
  ulem \
  makecell
  

