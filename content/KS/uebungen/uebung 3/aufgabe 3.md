```
10.65.128.0/18
```

# Bin
```
00001010.01000001.10000000.00000000
11111111.11111111.11000000.00000000 (/18)
11111111.11111111.11100000.00000000 (/19)
```

# Netzwerk-IDs (bin)

```
00001010.01000001.10000000.00000000 (Bereich A)
00001010.01000001.10100000.00000000 (Bereich B)
                    ^
```

> [!check] Richtig

# Netzwerk-IDs

## Bereich A

```
10.65.128.0/19
```

## Bereich B

```
10.65.160.0/19
```

> [!check] Richtig

# Interface-IDs

## Bereich A

```
10.65.128.0 - 10.65.159.254
```

> [!warning] Netzwerk- und Broadcastadresse abziehen
> `10.65.128.1 - 10.65.159.254`

## Bereich B

```
10.65.160.0 - 10.65.191.254
```

> [!warning] Netzwerk- und Broadcastadresse abziehen
> `10.65.160.1 - 10.65.191.254`

# Broadcast-Adressen

## Bereich A

```
10.65.159.255
```

## Bereich B

```
10.65.191.255
```

> [!check] Richtig
