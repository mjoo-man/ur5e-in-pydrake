# ur5e model

the ur5e.urdf was generated from this repo https://github.com/UniversalRobots/Universal_Robots_ROS2_Description/tree/humble

I used this commaned in the urdf directory of the above repo
 `xacro -o ur5e.urdf ur.urdf.xacro name:=ur5e ur_type:=ur5e`

 and edited the config yaml files to generate the .obj meshes
 the .dae and .stl meshes were converted to .obj using meshlab
