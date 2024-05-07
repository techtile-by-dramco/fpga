# USRP FPGA B210 Files

## FPGA bin description

| File | Description |
| --- | --- |
| TODO | List all new or modified files |
| TODO |  List all new or modified files |

## Loading the bin files

### Load the file into the USRP

```sh
uhd_image_loader --args="type=b200" --no-fw --fpga-path="./usrp_b210_fpga.bin"
```

### Load the file into the USRP in GNURadio

Include in the `Device Arguments` of the [USRP source or sink](https://wiki.gnuradio.org/index.php/USRP_Source): `fpga=/path/to/bitfile.bin`


### Load the file into the USRP in UHD

```python
usrp = uhd.usrp.MultiUSRP("fpga=/home/pi/experiments/00_calibration/usrp_b210_fpga.bin")
```
