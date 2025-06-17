system: ubuntu 24 desktop, installé sur SSD disk
Hardware: dell Opti Dlex 3020, sda disk macanique 8T, sdb SSD disk 500G
Preparation volumes:

```
# 只需创建目录（无需chown）
sudo mkdir -p /mnt/orthanc-storage
sudo mkdir -p /opt/orthanc-postgres-data

# 挂载HDD（仅需执行一次）
echo "/dev/sda2 /mnt/orthanc-storage ext4 defaults,nofail 0 2" | sudo tee -a /etc/fstab
sudo mount -a
```

```

```
