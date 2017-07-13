# Get caffe-fast-rcnn

  git clone --recursive git@github.com:rbgirshick/caffe-fast-rcnn.git
  cd caffe-fast-rcnn

# Commit hash used for py-faster-rcnn 2015 paper

  git checkout 0dcd397b29507b8314e252e850518c5695efbb83

# Merge caffe master branch

  git remote add caffe https://github.com/BVLC/caffe.git
  git fetch caffe
  git merge caffe/master
