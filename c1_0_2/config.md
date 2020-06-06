Parameter | Value |  
| ------ | ------ |  
| env_name | SpaceInvadersNoFrameskip-v4 |  
| hostname | cosy15 |  
| nn_size | AtariSize.LARGE |  
| nn_learn_rate | 0.00025 |  
| nn_adam_eps | 1e-05 |  
| nn_input_shape | (4, 84, 84) |  
| nn_max_gradient_norm | 0.5 |  
| max_time_steps | 10000000 |  
| horizon | 128 |  
| gae_discount | 0.99 |  
| gae_weight | 0.95 |  
| ppo_num_envs | 8 |  
| ppo_epochs | 4 |  
| ppo_num_mini_batches | 4 |  
| ppo_clipping_parameter | 0.1 |  
| ppo_value_function_coeff | 0.2 |  
| ppo_entropy_coeff | 0.01 |  
| ppo_use_linear_decay | True |  
| torch_seed | 11337885241829537266 |  
| atari_seed | 1588439764 |  
