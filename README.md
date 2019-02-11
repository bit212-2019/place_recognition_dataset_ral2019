# V4RL Wide-baseline Place Recognition Dataset
This dataset provides synthetic and real outdoors sequences especially recorded for place recognition applications using both flying and hand-held setups. This dataset was made publicly available with the paper "Real-time Wide-baseline Place Recognition using Depth Completion", by Fabiola Maffra, Lucas Teixeira, Zetao Chen and Margarita Chli, published at IEEE Robotics and Automation Letters (RA-L) 2019 [[paper](https://doi.org/10.1109/lra.2019.2895826)].

#### Video:
<a href="https://youtu.be/iwxbxAsCJbM" target="_blank"><img src="png" 
alt="intro" width="240" height="180" border="10" /></a>


If you use this dataset, please cite the following publication:
 
```
@article{maffra2019real,
  title={Real-time Wide-baseline Place Recognition using Depth Completion},
  author={Maffra, Fabiola and Teixeira, Lucas and Chen, Zetao and Chli, Margarita},
  journal={IEEE Robotics and Automation Letters},
  year={2019},
  publisher={IEEE}
}
```

## L'Agout dataset

The L'Agout synthetic dataset was produced using aerial pictures of “Maisons sur l’Agout” visible in Fig. 5, depicting medieval houses with balconies over the river Agout. We produce 4 sequences of 100 meters with a laterally moving drone carrying a camera facing the houses at 0° (i.e. pointing forwards), 15° from the horizon, 30°, and 45° as shown in Fig. 6b. It is important to highlight that the position of the drone was chosen in a way that the camera frustum is completely filled by the buildings in order to guarantee that the only difference between these sequences happens in the viewpoint, without any changes in scale. By combining sequences at different angles, large changes in viewpoint can be simulated and a very challenging place recognition dataset is created. 


### Examples
<a href="Youtube" target="_blank"><img src="png" 
alt="shop1_seq1" width="200"  border="10" /></a>
<a href="Youtube" target="_blank"><img src="png" 
alt="shop1_seq2" width="200"  border="10" /></a>
<a href="Youtube" target="_blank"><img src="png" 
alt="shop2_seq1" width="200"  border="10" /></a>

### Data

**L'Agout Sequence 0°**  - [Bagfile](Bagfile) - [Youtube](Youtube)

**L'Agout Sequence 15°** - [Bagfile](Bagfile) - [Youtube](Youtube)
 
**L'Agout Sequence 30°** - [Bagfile](Bagfile) - [Youtube](Youtube)

**L'Agout Sequence 45°** - [Bagfile](Bagfile) - [Youtube](Youtube)

### Ground truth

The ground truth for each dataset was manually annotated using 2 different sequences, a query sequence and a reference sequence. The sequences used as reference and query for the available ground truth are:

* L'Agout Sequence 0° & Sequence 15°:

  - Reference Dataset: L'Agout Sequence 0°
  - Query Dataset    : L'Agout Sequence 15°

* L'Agout Sequence 0° & Sequence 30°:

  - Reference Dataset: L'Agout Sequence 0°
  - Query Dataset    : L'Agout Sequence 30°

* L'Agout Sequence 0° & Sequence 45°:

  - Reference Dataset: L'Agout Sequence 0°
  - Query Dataset    : L'Agout Sequence 45°

More details about the ground truth are available on the links below.

**L'Agout Sequence 0° & Sequence 15°** - [Ground truth](Ground truth)

**L'Agout Sequence 0° & Sequence 30°** - [Ground truth](Ground truth)

**L'Agout Sequence 0° & Sequence 45°** - [Ground truth](Ground truth)

                                           
## Corvin dataset

The Corvin dataset was produced using aerial footage of the Corvin Castle visible in Figs. 4 and 6. We produced 3 sequences at 0° , 30° , and 45° , while doing a300-meter circular flight around the castle. These sequences capture a scene composed of a large range of different depths.

### Data

**Corvin Sequence 0°**  - [Bagfile](Bagfile) - [Youtube](Youtube)

**Corvin Sequence 30°** - [Bagfile](Bagfile) - [Youtube](Youtube)
 
**Corvin Sequence 45°** - [Bagfile](Bagfile) - [Youtube](Youtube)

### Ground truth

* Corvin Sequence 0° & Sequence 30°:

  - Reference Dataset: Corvin Sequence 0°
  - Query Dataset    : Corvin Sequence 30°

* Corvin Sequence 0° & Sequence 45°:

  - Reference Dataset: Corvin Sequence 0°
  - Query Dataset    : Corvin Sequence 45°

More details about the ground truth are available on the links below.

**Corvin Sequence 0° & Sequence 30°** - [Ground truth](Ground truth)

**Corvin Sequence 0° & Sequence 45°** - [Ground truth](Ground truth)


## Old City dataset

Two sequences were recorded at the end of the day in the old city of Zurich, exhibiting not only small, but also challenging viewpoint variations due to the presence of narrow passages in this area, providing wide range of viewpoints of the same places. This dataset comprises two traverses along the same route, each one covering a distance of approximately 230 meters. In total, 10 minutes of data were recorded for this dataset.

### Examples
<a href="Youtube" target="_blank"><img src="png" 
alt="uav_seq1" width="200"  border="10" /></a>
<a href="Youtube" target="_blank"><img src="png" 
alt="uav_seq2" width="200"  border="10" /></a>

### Data

**Old City Sequence 1** - [Bagfile](Bagfile) - [Youtube](Youtube)

**Old City Sequence 2** - [Bagfile](Bagfile) - [Youtube](Youtube)

### Ground truth

* Old City Sequence 1 & 2:

  - Reference Dataset: Old City Sequence 1
  - Query Dataset    : Old City Sequence 2

More details about the ground truth are available on the links below.

**Old City Sequence 1 & 2** - [Ground truth](Ground truth)


## Clausius Street dataset (Air-Ground)

Clausius Street dataset consists of both an air-sequence and a hand-held sequence recorded on the same day along a residential street with the camera facing the buildings of one street side. These combined sequences present extreme viewpoint changes with images captured from a very wide baseline (air to ground).

### Examples
<img src="https://i.imgur.com/vrTF94V.png" alt="clausius_ground_1" width="200"  border="10" />
<img src="https://i.imgur.com/th8cFpr.png" alt="clausius_air_1" width="200"  border="10" />
<img src="https://i.imgur.com/dQEYvfX.png" alt="clausius_ground_2" width="200"  border="10" />
<img src="https://i.imgur.com/9BKY6Mn.png" alt="clausius_air_2" width="200"  border="10" />

### Data

**Clausius Street Air Sequence**    - [Bagfile](Bagfile) - [Youtube](Youtube)

**Clausius Street Ground Sequence** - [Bagfile](Bagfile) - [Youtube](Youtube)

### Ground truth

* Clausius Street Air-Ground Sequence:

  - Reference Dataset: Clausius Street Air Sequence
  - Query Dataset    : Clausius Street Ground Sequence

More details about the ground truth are available on the links below.

**Clausius Street Air-Ground Sequence** - [Ground truth](Ground truth)








### Calibration

The images were captured using a [VI-Sensor](http://wiki.ros.org/vi_sensor) and calibrated using [ETHZ ASL Kalibr](https://github.com/ethz-asl/kalibr). Below are the calibration parameters. Note that T_SC is the transformation from the Camera to the Sensor (IMU). The set of values correspond to camera0's intrinsics.

```python

- {T_SC:     
    [ 0.9999921569165363, 0.003945890103835121, 0.0003406709575200133, -0.030976405894694664,        
     -0.003948017768440125, 0.9999711543561547, 0.0064887295612456805, 0.003944069243840622,         
     -0.00031505731688472255, -0.0064900236445916415, 0.9999788899431723, -0.016723945219020563,
     0.0, 0.0, 0.0, 1.0],
    image_dimension: [752, 480],
    distortion_coefficients: [0.0038403216668672986, 0.025065957244781098, -0.05227986912373674, 0.03635919730588422],
    distortion_type: equidistant,
    focal_length: [464.2604856754006, 463.0164764480498],
    principal_point: [372.2582270417875, 235.05442086962864]}

```

### Contact

For any questions or bug reports, please create an issue or contact me at fmaffra@mavt.ethz.ch.
