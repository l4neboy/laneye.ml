# laneye.ml

venv:
source laneyeenv/bin/activate

services:
laneye
postgresql


systemctl status laneye
systemctl status postgresql

systemctl stop <service>
systemctl start <service>
systemctl restart <service>
