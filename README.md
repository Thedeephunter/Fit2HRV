# Fit2HRV
# 从 fit 文件中获取 HRV
还在因为厂商的精准刀法不提供心率变异性 （HRV）闷闷不乐吗，让我们直接从 fit 文件里推测您的心率变异性吧
您在运动设备上保存的活动多半以 fit 文件的形式存储，即使无法获取准确的心率波形，也可以依据 fit 文件推算心率变异性
依据本项目，您可以：
 - 基于您的运动记录设备记录数分钟的静息状态并保存，由此推测出您的静息 HRV
 - 计算运动过程中的 HRV ，即使您的设备不提供 HRV 监测功能

**Warning** 本项目推算的 HRV 存在误差，若与您的运动设备监测值存在冲突请以监测值为准，此外，这一推测值不足以用于任何医疗活动
