# ConditionalTrigger

## Name
shallowflow.base.controls.ConditionalTrigger

## Synopsis
Executes the sub-flow whenever a token arrives before forwarding it only if the boolean condition evaluates to 'True'.

## Flow input/output
input: -unknown-

## Options
* debug (bool)

  * If enabled, outputs some debugging information
  * default: False

* skip (bool)

  * Whether to skip this actor during execution
  * default: False

* annotation (str)

  * For adding documentation to the actor
  * default: ''

* name (str)

  * The name to use for this actor, leave empty for class name
  * default: ''

* stop_flow_on_error (bool)

  * Whether to stop the flow in case of an error
  * default: True

* actors (list)

  * The sub-actors to manage
  * default: []

* condition (AbstractBooleanCondition)

  * The boolean condition to use
  * default: <shallowflow.base.conditions._Basic.AlwaysTrue object at 0x7fa23b9201c0>

