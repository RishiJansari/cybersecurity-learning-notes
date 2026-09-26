# Networking Basics

## IP Address
An IP address (Internet Protocol address) is a numerical identifier assigned to a device connected to a network.

### IPv4
```text
192.168.1.1
```

### IPv6
```text
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```

## Subnet
A subnet is a smaller network within a larger network. IP addressing and subnet configuration determine which devices belong to the same local network.

## Subnet Mask
A subnet mask divides an IPv4 address into network and host portions.

Example:
```text
255.255.255.0
```

## Default Gateway
A default gateway is usually a router that provides a path from the local network to other networks.

## `ping`
`ping` tests whether a host is reachable over an IP network. It sends ICMP Echo Requests and waits for Echo Replies.

```bash
ping google.com
ping 192.168.1.1
```

Useful output includes response time, TTL and packet loss.

## `tracert`
`tracert` is a Windows command used to trace the path toward a destination. It uses TTL values and responses from intermediate routers.

It can help investigate network paths, latency and where connectivity problems may occur.

## Common connectivity issues
My notes cover:
- Connection drops
- DNS/name-resolution problems
- Packet loss
- IP address conflicts
- Network configuration errors
- Hardware or connection problems
