## Learn command
### Panasonic U9XKH-8
```yaml
service: remote.learn_command
data:
  device: U9XKH-8
  command_type: ir
  alternative: true
  command:
    - Power
    - TemperatureUp
    - TemperatureDown
target:
  area_id: tent
  device_id: 03ee0da96f940772c2a837407bd9fe26
  entity_id: remote.tent_s_remote
  ```
### Panasonic F409M
```yaml
service: remote.learn_command
data:
  device: F409MG
  command_type: ir
  command:
    - Power
    - Speed
    - Swing
    - Timer
target:
  area_id: tent
  device_id: 03ee0da96f940772c2a837407bd9fe26
  entity_id: remote.tent_s_remote
  ```
