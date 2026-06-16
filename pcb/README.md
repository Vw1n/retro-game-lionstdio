# Table of contents
- [Eletronic component](#ec)
- [Manufacture](#manufacture)
- [Building](#building)
- [Flashing](#flashing)

# Eletronic component
TBD

# Manufacture
JLC pcb service. parameter:\
1mm thiness, 2 layers

# Building
## environment
recommand Ubuntu + esp-idf5.5.4

## build
source {path to esp-idf}/export.sh
### esp32s3
python rg_tool.py --target esp32-s3-devkit build-img 
### esp32p4
python rg_tool.py --target esp32-s3-devkit build-img --no-networking

# Flashing
TBD