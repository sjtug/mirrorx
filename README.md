# mirrorx
cached reverse proxy for software mirrors

## Arch
```
(Upstream)  ----[https]----     Squid3(cache)   --------    Nginx   ----[https://mirrorx.sjtug.org]
                                Static index.html--------/

                                |:-------------------------- Mirror x ---------------------------:|
```

## Initiative

- version insensitivity
- consistency insensitivity
- high locality
