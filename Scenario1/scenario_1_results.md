# Scenario 1 results:
## explanation for abbreviations in tables:
| ***abbreviation***      | ***explanation***                                     |
|:-----------------------:|:-----------------------------------------------------:|
| ***`U_V`***             | average number of updates between victims             |
| ***`E`<sub>`X`</sub>*** | average $\pm$ error value for the column `X`          |
| ***`S`***               | average percent of attacker's synchronization         |
| ***`U_A`***             | average number of attacker's updates                  |
| ***`P_V`***             | average victims' synchronization percent per update   |
| ***`P_A`***             | average attacker's synchronization percent per update |
## hebbian, random keys:
### table with results:
| ***`K`*** | ***`U_V`*** | ***`E`<sub>`U_V`</sub>*** | ***`S`*** | ***`E`<sub>`S`</sub>*** | ***`U_A`*** | ***`E`<sub>`U_A`</sub>*** | ***`P_V`*** | ***`E`<sub>`P_V`</sub>*** | ***`P_A`*** | ***`E`<sub>`P_A`</sub>*** |
|-----------|-------------|---------------------------|-----------|-------------------------|-------------|---------------------------|-------------|---------------------------|-------------|---------------------------|
| 5         | 57.06       | 4.25                      | 65.32     | 0.38                    | 15.52       | 1.09                      | 4.716       | 0.237                     | 10.412      | 0.516                     |
| 6         | 71.43       | 5.83                      | 64.56     | 0.33                    | 21.76       | 1.73                      | 4.081       | 0.268                     | 8.956       | 0.506                     |
| 7         | 113.43      | 9.34                      | 64.24     | 0.29                    | 38.82       | 3.21                      | 2.613       | 0.153                     | 5.264       | 0.311                     |
| 8         | 133.69      | 9.84                      | 64.6      | 0.27                    | 53.4        | 3.99                      | 2.28        | 0.117                     | 4.04        | 0.244                     |
| 9         | 208.72      | 14.34                     | 63.95     | 0.24                    | 92.03       | 6.43                      | 1.437       | 0.072                     | 2.323       | 0.17                      |
| 10        | 282.42      | 17.06                     | 64.04     | 0.24                    | 136.87      | 8.35                      | 0.999       | 0.047                     | 1.396       | 0.081                     |
| 11        | 281.47      | 14.98                     | 63.95     | 0.22                    | 149.88      | 8.2                       | 0.904       | 0.043                     | 1.152       | 0.065                     |
| 12        | 390.02      | 17.65                     | 63.67     | 0.22                    | 223.65      | 10.23                     | 0.574       | 0.021                     | 0.66        | 0.027                     |
| 13        | 393.54      | 18.1                      | 63.32     | 0.21                    | 239.95      | 11.21                     | 0.57        | 0.022                     | 0.615       | 0.026                     |
| 14        | 460.05      | 17.81                     | 63.46     | 0.2                     | 297.16      | 11.62                     | 0.442       | 0.018                     | 0.449       | 0.02                      |

### synch chart
![Synchronization percent per update](/charts/1_synch/1_K_synch_hX.png)
### update chart
![Attacker's synchronization and updates](/charts/1_update/1_K_update_hX.png)
