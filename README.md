# get-instagram-profile-avatar
Download Instagram profile photo via high speed api


Use this api via curl

```
curl -r 0-20000 -o my-avatar.png https://inbo.ir/avatar.php?u=[username]

```

Use php

```
header('Content-type: image/jpeg');

echo file_get_contents("https://inbo.ir/avatar.php?u=[username]");
```
