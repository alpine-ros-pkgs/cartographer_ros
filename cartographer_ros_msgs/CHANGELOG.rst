^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cartographer_ros_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Migrate to Alpine ROS 1 (`#1 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1>`_)
* Fix build status on front page. (`#1483 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1483>`_)
* Simplify start_trajectory service (RFC-28) (`#1245 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1245>`_)
* Service to query trajectory segments from the pose graph. (`#1222 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1222>`_)
* move metrics messages at root of msg folder (`#1020 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1020>`_)
* feat: Publish progress of processing the bagfile (`#940 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/940>`_)
* Add include_unfinished_submaps parameter to SerializeState() (`#966 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/966>`_)
* List files explicitly in cartographer_ros_msgs/CMakeLists.txt (`#927 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/927>`_)
* Use 'landmarks' instead of 'landmark'. (`#931 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/931>`_)
* Register internal metrics and provide a public interface. (`#917 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/917>`_)
* Add internal metric families. (`#914 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/914>`_)
* Allow to ignore (un-)frozen submaps in the occupancy grid node. (`#899 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/899>`_)
* Use PoseGraphInterface::TrajectoryState from libcartographer (`#910 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/910>`_)
* Release 1.0. (`#889 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/889>`_)
* Add maintainers and authors to package.xml (`#886 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/886>`_)
* [cartographer_ros_msgs] Message dependency fixup (`#882 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/882>`_)
* [cartographer_ros_msgs] add run dependency on message_runtime (`#800 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/800>`_)
* Pass ROS landmark topic to the cartographer. (`#746 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/746>`_)
* Add a ROS message for landmark observations. (`#732 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/732>`_)
* Add option to publish a pure 2D pose. (`#683 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/683>`_)
* Refactor ROS service responses. (`#708 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/708>`_)
* Wiring for sensor_msgs::NavSatFix (`#659 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/659>`_)
* Contributors: Alexander Belyaev, Alireza, Atsushi Watanabe, Michael Grupp, Mikael Arguedas, Susanne Pielawa, Wolfgang Hess, mgladkova

0.3.0 (2017-11-23)
------------------
* https://github.com/googlecartographer/cartographer_ros/compare/0.2.0...0.3.0

0.2.0 (2017-06-19)
------------------
* https://github.com/googlecartographer/cartographer_ros/compare/0.1.0...0.2.0

0.1.0 (2017-05-18)
------------------
* First unstable development release
