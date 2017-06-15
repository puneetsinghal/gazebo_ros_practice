## Quick Start

Rviz:

```
    roslaunch rrbot_description rrbot_rviz.launch
```

Gazebo:

```
    roslaunch rrbot_gazebo rrbot_world.launch
```

you can also export the GAZEBO_MODEL_PATH to see the leg model in gazebo:

```
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:(PATH TO RRBOT_DESCRIPTION/MODELS FOLDER)

```

The sdf file is created directly using command:

```
gzsdf print singleLeg.urdf > singleLeg.sdf 
```

The singleLeg.urdf file is in folder rrbot_description/urdf folder. This is still an open leg structure without foot assembly to close the chain