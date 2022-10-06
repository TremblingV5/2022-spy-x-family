# 数据说明文件

[TOC]

## crossing_node_data.csv

此数据为交通路口节点数据，表头如下：节点编号、路口横坐标、路口纵坐标

## crossing_node_line_data.csv

此数据为交通路口路线数据，表头如下：路线编号、路线起点、路线终点、路线距离；路线起点和路线终点对应`crossing_node_data.csv`中的节点编号。

## residential_area_data.csv

此数据为各区主要小区数据，表头如下：小区编号、小区栋数、小区户数、小区人口数、小区横坐标、小区纵坐标、街道编号、所属区域。

## population&launchPoints_nums.json

此数据为原题目的附件二，整理成了json格式。每个value为一个array，索引为0的项目为该区的人口数，索引为1的项目为该区的投放点的数量。
