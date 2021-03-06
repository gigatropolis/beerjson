The schema defines the following properties:

---

# Sub Schemas

The schema defines the following additional types:

## MashProcedureType
`MashProcedureType` (object)

MashProcedureType defines the procedure for performing unique mashing styles

Properties of the `MashProcedureType` object:

* [name](#name)
* [grain_temperature](#grain_temperature)
* [sparge_temperature](#sparge_temperature)
* [pH](#pH)
* [notes](#notes)
* [mash_steps](#mash_steps)

### name
 `name` (string, required)

### grain_temperature
 `grain_temperature` ([TemperatureType](measureable_units.json.md/#temperaturetype), required)

### sparge_temperature
 `sparge_temperature` ([TemperatureType](measureable_units.json.md/#temperaturetype))

### pH
 `pH` (number)

### notes
 `notes` (string)

### mash_steps
 `mash_steps` (object, required)

Properties of the `mash_steps` object:

* [step](#step)

#### step
 `step` ([MashStepType](mash_step.json.md/#mashsteptype), required)