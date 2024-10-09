# draw_mifi_ping

● Online draw : https://dustinchen26.github.io/draw_mifi_ping

## Example

● Input below command in Saviah CN: 

ping 10.205.164.22 -c 21600 | while read pong; do echo "$(date -u +"%Y-%m-%d %H:%M:%S"): $pong"; done

```
root@compal-saviah:~# ping 10.205.164.22 -c 21600 | while read pong; do echo "$(date -u +"%Y-%m-%d %H:%M:%S"): $pong"; done
2024-10-09 00:45:47: PING 10.205.164.22 (10.205.164.22) 56(84) bytes of data.
2024-10-09 00:45:47: 64 bytes from 10.205.164.22: icmp_seq=1 ttl=64 time=38.9 ms
2024-10-09 00:45:48: 64 bytes from 10.205.164.22: icmp_seq=2 ttl=64 time=26.9 ms
2024-10-09 00:45:49: 64 bytes from 10.205.164.22: icmp_seq=3 ttl=64 time=25.0 ms
```

● Output

```
Statistics
Max: 38.9 ms, Min: 25 ms, Avg: 30.27 ms
```