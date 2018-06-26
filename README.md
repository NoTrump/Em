# Em
Em算法实例

硬币实例，硬币混在一起，然后扔硬币，分析扔的是A还是B。

E步骤：
1.概率分布为伯努利分布，Q（z）求出后带入c_ik的期望，得出E——ci
M步骤：
2.更新theta值，重复上述两步。
结束条件：
if np.abs(loglike_new - loglike_old) < tolerance:
        break
