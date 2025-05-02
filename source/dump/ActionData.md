# ActionData

**Namespace:** ` `


## Fields

- `ActionType actionType`

- `Boolean managedByScheduler`

- `String key`

- `Int32 count`

- `Single preDelay`

- `Single interval`

- `Boolean useExtraRoute`

- `Int32 routeIndex`

- `Boolean blockFragment`

- `Boolean autoPreviewRoute`

- `Boolean autoDisplayEnemyInfo`

- `Boolean isUnharmfulAndAlwaysCountAsKilled`

- `String hiddenGroup`

- `String randomSpawnGroupKey`

- `String randomSpawnGroupPackKey`

- `RandomType randomType`

- `RefreshType refreshType`

- `Int32 weight`

- `Boolean dontBlockWave`

- `Boolean forceBlockWaveInBranch`

- `Boolean isValid`

- `Boolean notCountInTotal`

- `Object extraMeta`

- `ActionID actionId`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ActionData : IItemWithWeight
{
	public ActionType actionType; // 0x10
	public Boolean managedByScheduler; // 0x14
	public String key; // 0x18
	public Int32 count; // 0x20
	public Single preDelay; // 0x24
	public Single interval; // 0x28
	public Boolean useExtraRoute; // 0x2c
	public Int32 routeIndex; // 0x30
	public Boolean blockFragment; // 0x34
	public Boolean autoPreviewRoute; // 0x35
	public Boolean autoDisplayEnemyInfo; // 0x36
	public Boolean isUnharmfulAndAlwaysCountAsKilled; // 0x37
	public String hiddenGroup; // 0x38
	public String randomSpawnGroupKey; // 0x40
	public String randomSpawnGroupPackKey; // 0x48
	public RandomType randomType; // 0x50
	public RefreshType refreshType; // 0x54
	public Int32 weight; // 0x58
	public Boolean dontBlockWave; // 0x5c
	public Boolean forceBlockWaveInBranch; // 0x5d
	public Boolean isValid; // 0x5e
	public Boolean notCountInTotal; // 0x5f
	public Object extraMeta; // 0x60
	public ActionID actionId; // 0x68

	public Single weightValue { get; }

	// RVA: 0x34a42f8 VA: 0x7595abc2f8
	public Single get_weightValue() { }
	// RVA: 0x34a4304 VA: 0x7595abc304
	public Void .ctor() { }
}
```