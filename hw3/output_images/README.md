# 多机器渲染结果索引

## Part 4: Global Illumination
- 生成图片数量: 30
- 活跃渲染锁: 0
- 位置: output_images/part4/

## Part 5: Adaptive Sampling  
- 生成图片数量: 20
- 活跃渲染锁: 0
- 位置: output_images/part5/

## 统计信息
- 总计: 50 张图片
- 总计渲染锁: 0 个
- 总文件大小: 6.58 MB
- 生成时间: 2025-08-03 22:37:23

## 多机器使用说明
- 每台机器运行相同命令即可自动分工
- 文件锁机制防止重复渲染
- 占位图片仅在开始渲染时创建
- 锁文件超过1小时自动清理

## 使用说明
- python3 generate_images_part45_with_placeholder.py                    # 多机器并行渲染
- python3 generate_images_part45_with_placeholder.py --force           # 强制重新生成
- python3 generate_images_part45_with_placeholder.py --clean           # 清理损坏文件和僵死锁
- python3 generate_images_part45_with_placeholder.py --help            # 查看帮助
