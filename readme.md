# how to establish now cronjob(#環境是在Cpanel)
## 請取決自己的主機環境，不同的主機環境可能導致不同的主機路徑
```

cd /home/${hostName}/${projectStoreDirectory}/${project} && ${userprofile}/php artisan schedule:run >> /dev/null 2>&1
ex: userprofile="/usr/local/bin"
```