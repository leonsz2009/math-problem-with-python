# Example Package
你可以用这个库来解决一些数学问题
from py-math-problem import *
解决行程问题
相遇问题
a = meet_and_chase.meet()
时间
a = meet_and_chase.meet()
a.what_time(路程,速度1,速度2)
路程
a.what_distance(时间，速度1，速度2)
速度和
a.what_add_speed(时间,路程)
追及问题
b = meet_and_chase.chase()
时间
b.what_time(路程,速度1,速度2)
路程
b.what_distance(时间，速度1，速度2)
速度差
b.what_minus_speed(时间,路程)
解决几何问题
面积
a = geometry.area(一个写着边长的列表,形状的英文拼写)
周长
b = geometry.circumference(一个写着边长的列表,形状的英文拼写)
