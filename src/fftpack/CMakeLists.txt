# bar library
file(GLOB FFTPACK_LOCAL_SRC
  "*.f90"
  )
SET(FFTPACK_src ${FFTPACK_LOCAL_SRC})
ADD_LIBRARY(FFTPACKLIB OBJECT ${FFTPACK_src})
