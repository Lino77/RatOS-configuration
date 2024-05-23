## Common

```
variable_relative_extrusion: False
variable_force_absolute_position: False
variable_preheat_extruder: True
variable_preheat_extruder_temp: 150
variable_macro_travel_speed: 150
variable_macro_travel_accel: 2000
variable_macro_z_speed: 15
variable_bed_margin_x: [0, 0]
variable_bed_margin_y: [0, 0]
variable_printable_x_min: 0
variable_printable_x_max: 0
variable_printable_y_min: 0
variable_printable_y_max: 0
variable_end_print_motors_off: True
variable_status_color_ok: "00FF00"
variable_status_color_error: "FF0000"
variable_status_color_unknown: "FFFF00"
```

## Homing
```
variable_homing: "endstops"
variable_z_probe: "static"
variable_safe_home_x: "middle"
variable_safe_home_y: "middle"
variable_driver_type_x: "tmc2209"
variable_driver_type_y: "tmc2209"
variable_sensorless_x_current: 0.4
variable_sensorless_y_current: 0.4
variable_stowable_probe_stop_on_error: False
```

## Mesh

```
variable_calibrate_bed_mesh: True
variable_adaptive_mesh: True
variable_probe_for_priming_result: None
variable_probe_for_priming_result_t1: None
variable_probe_for_priming_end_result: None
variable_probe_for_priming_end_result_t1: None
variable_adaptive_prime_offset_threshold: -1.0
```

## Parking 

```
variable_start_print_park_in: "back"
variable_start_print_park_z_height: 50
variable_start_print_heat_chamber_bed_temp: 115
variable_end_print_park_in: "back"
variable_pause_print_park_in: "back"
variable_end_print_park_z_hop: 20
```

## Priming 

```
variable_nozzle_priming: "primeblob"
variable_nozzle_prime_start_x: "max"
variable_nozzle_prime_start_y: "min"
variable_nozzle_prime_direction: "auto"
variable_nozzle_prime_bridge_fan: 102
variable_last_z_offset: None
```

## IDEX 

```
variable_auto_center_subject: False
variable_toolchange_zhop: 2.0
variable_toolchange_zspeed: 25
variable_toolchange_sync_fans: False
variable_toolchange_combined_zhop: False
variable_toolchange_travel_speed: 300
variable_toolchange_travel_accel: 5000
variable_toolchange_extrusion: 2.0
variable_toolchange_retraction: 2.0
variable_toolchange_feedrate: 7200
variable_toolchange_prepurging_timer: 0
variable_toolchange_standby_temp: -1
variable_toolchange_purge: 25
variable_toolchange_first_purge: 50
```

## Stowable Probes

```
variable_stowable_probe_position_preflight: [ 30, 60 ]
variable_stowable_probe_position_side:      [  13, 60 ]
variable_stowable_probe_position_dock:      [   13, 6.5 ]
variable_stowable_probe_position_exit:      [   60, 6.5 ]
variable_stowable_probe_batch_mode_enabled: False
variable_stowable_probe_state: None
```

## Beacon 

```
variable_beacon_bed_mesh_scv: 25
variable_beacon_contact_z_homing: False
variable_beacon_contact_z_calibration: False
variable_beacon_contact_calibration_location: "center"
variable_beacon_contact_calibrate_margin_x: 30
variable_beacon_contact_bed_mesh: False
variable_beacon_contact_bed_mesh_samples: 2
variable_beacon_contact_z_tilt_adjust: False
variable_beacon_contact_z_tilt_adjust_samples: 2
variable_beacon_contact_prime_probing: False
variable_beacon_contact_calibration_temp: 170
```