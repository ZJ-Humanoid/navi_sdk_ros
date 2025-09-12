# /zj_humanoid/manipulation/grasp_teach_service

## description
- 视觉抓取示教服务

## type
- Service

## msg_type
- [GraspTeach](../../../../zj_humanoid_types.md#GraspTeach)

## demos
- rosservice call /zj_humanoid/manipulation/grasp_teach_service "{which_arm: 'right', object_label: 'object'}"

## agent
- 视觉示教抓取，让机器人知道该从什么方位抓取物品

