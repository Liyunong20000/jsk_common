^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package dynamic_tf_publisher
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.2.16 (2025-01-06)
-------------------

2.2.15 (2024-12-13)
-------------------

2.2.14 (2024-12-12)
-------------------

2.2.13 (2023-11-09)
-------------------

* add test to check if dynamic_tf_publisher/sample/sample.launch works (`#1788 <https://github.com/jsk-ros-pkg/jsk_common/issues/1788>`_)

  * fixed to import roslib.message explicitly
  * add test to check if dynamic_tf_publisher/sample/sample.launch works

* [dynamic_tf_publisher] Fix Python shebang for Noetic (`#1775 <https://github.com/jsk-ros-pkg/jsk_common/issues/1775>`_)

* Contributors: Kei Okada, Shingo Kitagawa, Wolfgang Merkt, Koki Amabe

2.2.12 (2022-06-07)
-------------------
* run 2to3 -w -f has_key for python3 compatibility (`#1695 <https://github.com/jsk-ros-pkg/jsk_common/issues/1695>`_)
* install tf_reconfigure_publisher.py (`#1654 <https://github.com/jsk-ros-pkg/jsk_common/issues/1654>`_)
* Contributors: Shingo Kitagawa

2.2.11 (2020-07-10)
-------------------
* Fix for noetic build (`#1648 <https://github.com/jsk-ros-pkg/jsk_common/issues/1648>`_)

  * fix for python3, except, print ....
  * upgrade package.xml to format=3

* Update package name so it does not produce extra lines in rospack list (`#1625 <https://github.com/jsk-ros-pkg/jsk_common/issues/1625>`_)

* Contributors: J-Rojas, Kei Okada

2.2.10 (2018-11-03)
-------------------

2.2.9 (2018-11-02)
------------------

2.2.8 (2018-11-01)
------------------
* Add comment about installation (`#1604 <https://github.com/jsk-ros-pkg/jsk_common/issues/1604>`_)
* Contributors: Yuto Uchimi

2.2.7 (2018-06-27)
------------------

2.2.6 (2018-01-05)
------------------

2.2.5 (2017-06-19)
------------------

2.2.4 (2017-06-14)
------------------
* add ROSIntrupptException, not to show strage message on shutting down (`#1522 <https://github.com/jsk-ros-pkg/jsk_common/pull/1522>`_)
* Contributors: Kei Okada

2.2.3 (2017-03-23)
------------------

2.2.2 (2016-12-30)
------------------

2.2.1 (2016-12-13)
------------------

2.2.0 (2016-10-28)
------------------

2.1.2 (2016-09-14)
------------------

2.1.1 (2016-09-07)
------------------

2.1.0 (2016-09-06)
------------------

2.0.17 (2016-07-21)
-------------------

2.0.16 (2016-06-19)
-------------------

2.0.15 (2016-06-13)
-------------------

2.0.14 (2016-05-14)
-------------------

2.0.13 (2016-04-29)
-------------------

2.0.12 (2016-04-18)
-------------------

2.0.11 (2016-03-20)
-------------------
* remove dynamic_reconfigure.parameter_generator, which only used for rosbuild
* Contributors: Kei Okada

2.0.10 (2016-02-13)
-------------------
* [tf_publisher.py] do not import genpy since it is not used
* [tf_publish.py] remove backward compatibility
* queue_size is new in hydro and necessary from indigo
* Contributors: Eisoku Kuroiwa

2.0.9 (2015-12-14)
------------------

2.0.8 (2015-12-07)
------------------

2.0.7 (2015-12-05)
------------------

2.0.6 (2015-12-02)
------------------

2.0.5 (2015-11-30)
------------------

2.0.4 (2015-11-25)
------------------
* [dynamic_tf_publisher] Moreh helpful debug message and fix several typos
* [dynamic_tf_publisher] Use with to acquire lock
* [dynamic_tf_publisher] Advertise services at the last of initialization
* [dynamic_tf_publisher] Check service collision in launching tf_publish
* Contributors: Ryohei Ueda

2.0.3 (2015-07-24)
------------------

2.0.2 (2015-07-07)
------------------

2.0.1 (2015-06-28)
------------------

2.0.0 (2015-06-19)
------------------

1.0.72 (2015-06-07)
-------------------

1.0.71 (2015-05-17)
-------------------

1.0.70 (2015-05-08)
-------------------

1.0.69 (2015-05-05)
-------------------

1.0.68 (2015-05-05)
-------------------

1.0.67 (2015-05-03)
-------------------

1.0.66 (2015-04-03)
-------------------

1.0.65 (2015-04-02)
-------------------

1.0.64 (2015-03-29)
-------------------

1.0.63 (2015-02-19)
-------------------

1.0.62 (2015-02-17)
-------------------

1.0.61 (2015-02-11)
-------------------

1.0.60 (2015-02-03)
-------------------

1.0.59 (2015-02-03)
-------------------
* Remove rosbuild files
* Contributors: Ryohei Ueda

1.0.58 (2015-01-07)
-------------------

1.0.57 (2014-12-23)
-------------------

1.0.56 (2014-12-17)
-------------------

1.0.55 (2014-12-09)
-------------------
* import empty srv
* add pubish tf service
* Contributors: Yusuke Furuta

1.0.54 (2014-11-15)
-------------------
* Add tf publisher which can be reconfigured by dynamic_reconfigure
* Contributors: Ryohei Ueda

1.0.53 (2014-11-01)
-------------------
* change frequency
* Contributors: Yusuke Furuta

1.0.52 (2014-10-23)
-------------------

1.0.51 (2014-10-20)
-------------------

1.0.50 (2014-10-20)
-------------------

1.0.49 (2014-10-13)
-------------------

1.0.48 (2014-10-12)
-------------------

1.0.47 (2014-10-08)
-------------------

1.0.46 (2014-10-03)
-------------------

1.0.45 (2014-09-29)
-------------------

1.0.44 (2014-09-26)
-------------------

1.0.43 (2014-09-26)
-------------------

1.0.42 (2014-09-25)
-------------------

1.0.41 (2014-09-23)
-------------------

1.0.40 (2014-09-19)
-------------------

1.0.39 (2014-09-17)
-------------------

1.0.38 (2014-09-13)
-------------------

1.0.36 (2014-09-01)
-------------------

1.0.35 (2014-08-16)
-------------------

1.0.34 (2014-08-14)
-------------------
* not publish tf in service call
* Contributors: Yusuke Furuta

1.0.33 (2014-07-28)
-------------------

1.0.32 (2014-07-26)
-------------------

1.0.31 (2014-07-23)
-------------------

1.0.30 (2014-07-15)
-------------------

1.0.29 (2014-07-02)
-------------------

1.0.28 (2014-06-24)
-------------------

1.0.27 (2014-06-10)
-------------------

1.0.26 (2014-05-30)
-------------------

1.0.25 (2014-05-26)
-------------------

1.0.24 (2014-05-24)
-------------------

1.0.23 (2014-05-23)
-------------------

1.0.22 (2014-05-22)
-------------------

1.0.21 (2014-05-20)
-------------------

1.0.20 (2014-05-09)
-------------------

1.0.19 (2014-05-06)
-------------------

1.0.18 (2014-05-04)
-------------------

1.0.17 (2014-04-20)
-------------------

1.0.16 (2014-04-19)
-------------------

1.0.15 (2014-04-19)
-------------------

1.0.14 (2014-04-19)
-------------------

1.0.13 (2014-04-19)
-------------------

1.0.12 (2014-04-18)
-------------------

1.0.11 (2014-04-18)
-------------------

1.0.10 (2014-04-17)
-------------------

1.0.9 (2014-04-12)
------------------

1.0.8 (2014-04-11)
------------------

1.0.4 (2014-03-27)
------------------
* dynamic_tf_publisher: add rospy to depends

1.0.0 (2014-03-05)
------------------
* set all package to 1.0.0
* catkinize dynamic_tf_publisher
* revert commit rev 5550
* set use cache false by default
* add parameter to select whether to use cache or not
* fix the bug in dynamic_tf_publisher package
* see ROS_DISTRO to use genpy.message or roslib.message (old API)
* save tf-chain in rosparm, in case of when tf_publisher is respawned
* roslib/Header is old style
* debug delete callback to work /delete_tf service
* publish tfMessage to ~tf, because it will ease debugging,
  and add some debug print in assoc callback
* DissocTFRequest does not have child_frame, it has frame_id slot
* add delete tf service
* fix error check of assocTF
* fix bag when assoc service called again
* do not accept set_dynamic_tf service for assocd frames
* mv jtalk and pddl to 3rdparty directory
* Contributors: Ryohei Ueda, Kei Okada, Manabu Saito, Yusuke Furuta, kazuto
