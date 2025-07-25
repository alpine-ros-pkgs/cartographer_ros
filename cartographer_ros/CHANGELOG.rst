^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cartographer_ros
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.0 (2018-06-01)
----------------------
* https://github.com/googlecartographer/cartographer_ros/compare/0.3.0...1.0.0

1.0.1000 (2025-07-25)
---------------------
* Migrate to Alpine ROS 1 (`#1 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1>`_)
* Fix typos discovered by codespell (`#1684 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1684>`_)
* Add option to ignore out of order sensor message (`#1737 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1737>`_)
* Check if we already publihed transformation at same timestamp Fix `#1555 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1555>`_ (`#1556 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1556>`_)
* Use the MapBuilder factory function. (`#1551 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1551>`_)
* Use PoseGraphInterface instead of PoseGraph. (`#1547 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1547>`_)
* Make publishing tf optional, enable publishing PoseStamped (`#1099 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1099>`_)
* Follow `cartographer-project/cartographer#1759 <https://github.com/cartographer-project/cartographer/issues/1759>`_. (`#1525 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1525>`_)
* Fix includes to follow style guide in playable_bag.h (`#1524 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1524>`_)
* Follow `cartographer-project/cartographer#1749 <https://github.com/cartographer-project/cartographer/issues/1749>`_. (`#1516 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1516>`_)
* Changes for ROS Noetic support (`#1494 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1494>`_)
* Prepare GMock support for Noetic. (`#1499 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1499>`_)
* Build Abseil dependency in CI. (`#1485 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1485>`_)
* Fix build status on front page. (`#1483 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1483>`_)
* Remove unnecessary eigen_conversions dependency. (`#1278 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1278>`_)
* Simplify start_trajectory service (RFC-28) (`#1245 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1245>`_)
* Service to query trajectory segments from the pose graph. (`#1222 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1222>`_)
* Add explicit --save_state_filename to offline node options. (`#1204 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1204>`_)
* Unify trajectory state checks for service handlers. (`#1262 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1262>`_)
* Update clang-format to new Google style. (`#1260 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1260>`_)
* Extend trajectory export tool to write TransformStamped topics. (`#1169 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1169>`_)
* Replace a few string operator+ by absl::StrCat(). (`#1244 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1244>`_)
* Fix segfault by changing the destruction order. (`#1235 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1235>`_)
* Tool for extracting pbstream trajectories into bag with tf. (`#1166 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1166>`_)
* Publish one last progress message when PlayableBag is finished. (`#1160 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1160>`_)
* Don't run final optimization in visualize_pbstream.launch (`#1157 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1157>`_)
* Windows build & Azure CI (`#1103 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1103>`_)
* Configurable frame IDs in trajectory_comparison_main.cc (`#1120 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1120>`_)
* Add git dependency to package.xml (for Abseil build). (`#1098 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1098>`_)
* Consider waiting trajectories with a sensor bridge as active. (`#1089 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1089>`_)
* Only include correct source files in cmake (`#1085 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1085>`_)
* Add a script for testing with fake landmarks to scripts/dev (`#1071 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1071>`_)
* Transform landmark poses to the tracking frame. (`#1076 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1076>`_)
* Remove orphaned function in occupancy_grid_node_main.cc (`#1034 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1034>`_)
* Decrease asset writer progress log period (`#1044 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1044>`_)
* Fix Clang thread-safety warning. (`#1068 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1068>`_)
* Adding launch file arg for launch-prefix to offline nodes (`#1066 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1066>`_)
* Only use ROS log sink in pbstream_map_publisher_main.cc (`#1040 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1040>`_)
* fix: Use an explicit message_counter instead of using `std::distance` (`#1045 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1045>`_)
* Use absl::SkipEmpty() predicate. (`#1042 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1042>`_)
* Replace custom SplitString() by absl::StrSplit() (`#1026 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1026>`_)
* feat: Publish progress of processing the bagfile (`#940 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/940>`_)
* Follow `googlecartographer/cartographer#1424 <https://github.com/googlecartographer/cartographer/issues/1424>`_ (`#1014 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1014>`_)
* Disable forwarding proto stream by default in node_grpc_main.cc (`#1013 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1013>`_)
* Add --load_frozen_state to node_grpc_main.cc (`#973 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/973>`_)
* Removing unless from argument (`#994 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/994>`_)
* Adding generic parametrizable offline_node.launch (`#983 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/983>`_)
* Follow cartographer`#1357 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/1357>`_ (`#964 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/964>`_)
* Adding option to launch without rviz, similar to 2d case (`#972 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/972>`_)
* [ABSL] Use absl::Mutex. (`#969 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/969>`_)
* Add include_unfinished_submaps parameter to SerializeState() (`#966 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/966>`_)
* Follow `googlecartographer/cartographer#1353 <https://github.com/googlecartographer/cartographer/issues/1353>`_ (`#959 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/959>`_)
* Follow `googlecartographer/cartographer#1352 <https://github.com/googlecartographer/cartographer/issues/1352>`_ (`#957 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/957>`_)
* Follow the Absl update. (`#955 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/955>`_)
* Fix pbstream exporting binaries (`#945 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/945>`_)
* Add option to disable PoseExtrapolator (`#946 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/946>`_)
* Get rid of std::bind. (`#939 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/939>`_)
* Move conversion table to LoadOccupancyGridMap. (`#941 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/941>`_)
* Add .clang-format file. (`#938 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/938>`_)
* Introduce value converter tables. (`#937 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/937>`_)
* Warn for possible topic mismatch (`#935 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/935>`_)
* Simplify gauge and histogram implementation. (`#922 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/922>`_)
* remove unused declaration (`#934 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/934>`_)
* Follow `googlecartographer/cartographer#1241 <https://github.com/googlecartographer/cartographer/issues/1241>`_ (`#923 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/923>`_)
* Allow zero pose_publish_period (`#933 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/933>`_)
* Use 'landmarks' instead of 'landmark'. (`#931 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/931>`_)
* Fix bug in FinishTrajectory logic (`#926 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/926>`_)
* Update msg_conversion.cc (`#925 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/925>`_)
* Register internal metrics and provide a public interface. (`#917 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/917>`_)
* Use new pure localization trimmer options. (`#918 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/918>`_)
* Add internal metric families. (`#914 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/914>`_)
* Allow to ignore (un-)frozen submaps in the occupancy grid node. (`#899 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/899>`_)
* Discard proto data in pbstream_map_publisher via RAII. (`#912 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/912>`_)
* Use PoseGraphInterface::TrajectoryState from libcartographer (`#910 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/910>`_)
* Improve internal naming of local SLAM data. (`#908 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/908>`_)
* Revert timers other than PublishTrajectoryStates back to being WallTimers. (`#898 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/898>`_)
* Ensure we validate what we CHECK(...) (`#897 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/897>`_)
* Use timing channel from PointCloud2, if available.  (`#896 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/896>`_)
* Fix memory leak in simulations by removing wall timers. (`#891 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/891>`_)
* set required version of dependencies (`#892 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/892>`_)
* remove architecture specific definitions exported by PCL (`#893 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/893>`_)
* Release 1.0. (`#889 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/889>`_)
* Add maintainers and authors to package.xml (`#886 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/886>`_)
* Follow `googlecartographer/cartographer#1174 <https://github.com/googlecartographer/cartographer/issues/1174>`_ (`#883 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/883>`_)
* Follow `googlecartographer/cartographer#1172 <https://github.com/googlecartographer/cartographer/issues/1172>`_ (`#881 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/881>`_)
* Sanitize node memory consumption with a smaller TF buffer size. (`#879 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/879>`_)
* Follow `googlecartographer/cartographer#1164 <https://github.com/googlecartographer/cartographer/issues/1164>`_ (`#877 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/877>`_)
* Assets writer (ROS map) urdf typo fix (`#875 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/875>`_)
* Fix the 'load_frozen_state' flag in visualize_pbstream.launch. (`#863 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/863>`_)
* Follow `googlecartographer/cartographer#1143 <https://github.com/googlecartographer/cartographer/issues/1143>`_ (`#859 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/859>`_)
* Adapt to new mapping proto location of cartographer (`#860 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/860>`_)
* Use immediately invoked lambda for tracking_to_local. (`#848 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/848>`_)
* Add cartographer_dev_rosbag_publisher (`#854 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/854>`_)
* Follow up on https://github.com/googlecartographer/cartographer/pull/1108 (`#838 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/838>`_)
* Add a launch and configuration file for writing a ROS map (`#577 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/577>`_) (`#721 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/721>`_)
* Internal cleanup. (`#821 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/821>`_)
* Registration of external points processors in AssetsWriter (`#830 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/830>`_)
* Extract assets writer class from static method (`#827 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/827>`_)
* Enable rendering of submaps without a grid (`#829 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/829>`_)
* Assets writer refactoring (`#814 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/814>`_)
* Correct localization_3d.launch (`#824 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/824>`_)
* Internal cleanup. (`#818 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/818>`_)
* Take frozen state into account when finishing trajectories. (`#811 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/811>`_)
* Fix race-condition when attempting to fetch trimmed submaps. (`#812 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/812>`_)
* moved run method of assets writer main to separate files (`#807 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/807>`_)
* Check service status code in start_trajectory_main.cc (`#808 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/808>`_)
* Check overlapping range data correctly (`#804 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/804>`_)
* Fix sequential subdivisions (`#806 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/806>`_)
* Tool for comparing pure localization to offline optimization (`#803 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/803>`_)
* Show constraints in rviz (`#789 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/789>`_)
* Launch script to visualize pbstream in rviz (`#788 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/788>`_)
* Add constraint-dependent trajectory visualization. (`#756 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/756>`_)
* Avoid failed CHECK when running offline node with no bags. (`#777 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/777>`_)
* Ignore empty laser scan message. (`#767 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/767>`_)
* Minor optimizations of cases with no subscribers (`#755 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/755>`_)
* Add time skip option for offline node (`#680 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/680>`_)
* Follow https://github.com/googlecartographer/cartographer/pull/958. (`#754 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/754>`_)
* Follow https://github.com/googlecartographer/cartographer/pull/955. (`#751 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/751>`_)
* Pass ROS landmark topic to the cartographer. (`#746 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/746>`_)
* Follow PR [`#950 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/950>`_](https://github.com/googlecartographer/cartographer/pull/950). (`#750 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/750>`_)
* Fix pbstream_map_publisher (follow `#712 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/712>`_) (`#745 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/745>`_)
* s/LoadMap/LoadState in node_grpc_main.cc (`#744 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/744>`_)
* Offline multi-trajectory: use topic names without 'bag_n\_' prefix by default (`#707 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/707>`_)
* Use CreateOccupancyGridMsg() in occupancy_grid_node_main.cc (`#715 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/715>`_)
* Unfrozen trajectories (`#710 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/710>`_)
* Fix the path to mapping\_*d includes. (`#736 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/736>`_)
* Validate tool checks per-point time stamps. (`#737 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/737>`_)
* Add option to publish a pure 2D pose. (`#683 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/683>`_)
* Follow  `googlecartographer/cartographer#922 <https://github.com/googlecartographer/cartographer/issues/922>`_ (`#734 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/734>`_)
* Avoid auto for Eigen expressiongs. (`#719 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/719>`_)
* RViz settings for landmarks. (`#717 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/717>`_)
* Publish Landmark markers for RViz. (`#713 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/713>`_)
* Add pbstream_map_publisher_main.cc (`#711 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/711>`_)
* Follow `googlecartographer/cartographer#859 <https://github.com/googlecartographer/cartographer/issues/859>`_ (`#712 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/712>`_)
* Refactor ROS service responses. (`#708 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/708>`_)
* Offline node: better support for sequential bags. (`#694 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/694>`_)
* Follow `googlecartographer/cartographer#839 <https://github.com/googlecartographer/cartographer/issues/839>`_ (`#686 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/686>`_)
* Do not forget to finish trajectory if last message is not from a sensor topic (`#681 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/681>`_)
* Fix segfault in rosbag_validate (`#685 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/685>`_)
* Add a launch file for 2d localization demo with gRPC. (`#682 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/682>`_)
* Simultaneous offline multi trajectories (`#636 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/636>`_)
* Constraints visualization: Separate inter constraints between separate trajectories (`#634 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/634>`_)
* Fix gflags include in offline nodes (`#677 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/677>`_)
* Fix gflags include in offline_node.cc (`#676 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/676>`_)
* Deduplicate loading options for offline node (`#664 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/664>`_)
* Adding NavSatFix to trajectory builder. (`#666 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/666>`_)
* Transform from ECEF to a local frame where z points up. (`#662 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/662>`_)
* Wiring for sensor_msgs::NavSatFix (`#659 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/659>`_)
* Adding conversion from WGS84 to ECEF. (`#660 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/660>`_)
* Follow `googlecartographer/cartographer#801 <https://github.com/googlecartographer/cartographer/issues/801>`_ (`#657 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/657>`_)
* Add rviz and simtime to gRPC launch file. (`#658 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/658>`_)
* Fix bug in MapBuilderBridge::GetTrajectoryStates() (`#652 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/652>`_)
* Use GetTrajectoryNodePoses and GetAllSubmapPoses in GetConstraintList (`#651 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/651>`_)
* Make MapBuilderBridge use GetAllTrajectoryNodePoses() (`#649 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/649>`_)
* Make MapBuilderBridge::GetSubmapList() use GetAllSubmapPoses() (`#647 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/647>`_)
* Implement offline gRPC bridge. (`#645 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/645>`_)
* Fix path for gRPC server shell script in CMakeLists.txt (`#644 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/644>`_)
* Refactor offline_node_main.cc to prepare for offline bridge. (`#643 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/643>`_)
* Follow `googlecartographer/cartographer#782 <https://github.com/googlecartographer/cartographer/issues/782>`_ (`#633 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/633>`_)
* Launch grpc client and server (`#641 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/641>`_)
* Implement cartographer_grpc_node. (`#632 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/632>`_)
* Add BUILD_GRPC CMake flag and ROS-gRPC binary. (`#631 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/631>`_)
* HandleRangefinder time refers to newest point. (`#612 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/612>`_)
* Follow `googlecartographer/cartographer#736 <https://github.com/googlecartographer/cartographer/issues/736>`_ (`#620 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/620>`_)
* Detect duplicate range data. (`#619 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/619>`_)
* Fix 0. constant to 0.0 to comply with YAML standard (`#618 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/618>`_)
* Validate IMU, odometry, timing, frame names. (`#615 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/615>`_)
* Follow googlecartographer/cartographer/pull/724. (`#616 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/616>`_)
* Add initial_pose in start_trajectory_main.cc Fixes `#579 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/579>`_ (`#610 <https://github.com/alpine-ros-pkgs/cartographer_ros/issues/610>`_)
* Contributors: Alexander Belyaev, Alireza, Atsushi Watanabe, Christian Clauss, Christoph Schütte, Guilherme Lawless, Jihoon Lee, Jonathan Huber, Juraj Oršulić, Kevin Daun, Linh Nguyen, Martin Schwörer, Matthias Loebach, Michael Grupp, Mikael Arguedas, Roel, Sebastian Klose, Susanne Pielawa, Wolfgang Hess, gaschler, jie, mgladkova, stribor14

0.3.0 (2017-11-23)
------------------
* https://github.com/googlecartographer/cartographer_ros/compare/0.2.0...0.3.0

0.2.0 (2017-06-19)
------------------
* https://github.com/googlecartographer/cartographer_ros/compare/0.1.0...0.2.0

0.1.0 (2017-05-18)
------------------
* First unstable development release
