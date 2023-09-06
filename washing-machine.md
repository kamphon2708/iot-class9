# Washing machine state

## START
topic:v1cdti/hw/set/6310301011/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
     "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FILLWATER"

}

## HEATWATER
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
     "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEATWATER"
    
}

## WASH
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
     "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WASH"
}

## RINSE
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
     "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "RINSE"
}

## SPIN
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
     "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "SPIN"
}

# Operation state

## DOORCLOSE
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
     "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "DOORCLOSE",
    "value"     :   "0|1"
}

## WATERFULLLEVEL
topic:v1cdti/hw/set/6310301011/model-01/sn-01
payload: {
     "action"    :   "set",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "WATERFULLLEVEL",
    "value"     :   "0|1"
}

## TEMPERATUREREACHED
topic:v1cdti/hw/set/6310301011/model-01/sn-01
payload: {
     "action"    :   "set",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "TEMPERATUREREACHED",
    "value"     :   "30"
}
## FunctionCompleted
topic:v1cdti/hw/set/6310301011/model-01/sn-01
payload: {
     "action"    :   "set",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Function_compleate",
    "value"     :   "0|1"
}

# FAULT state

## TIMEOUT
topic:v1cdti/hw/get/6310301011/model-01/sn-01
payload: {
     "action"    :   "get",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "TIMEOUT"
}

## OUTOFBALANCE
topic:v1cdti/hw/set/6310301011/model-01/sn-01
payload: {
     "action"    :   "set",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "OUTOFBALANCE"
}

## MOTORFAILURE
topic:v1cdti/hw/set/6310301011/model-01/sn-01
payload: {
     "action"    :   "set",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "MOTORFAILURE"
}

## FAULTCLEARED
topic:v1cdti/hw/set/6310301011/model-01/sn-01
payload: {
     "action"    :   "set",
    "project"   :   "6310301011",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "FAULTCLEARED"
}