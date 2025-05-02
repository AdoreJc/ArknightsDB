# Act5D1StageController

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1InitMeta m_initMetaObj`


## Properties

- `Act5D1InitMeta initMetaObj`


## Methods

- `Act5D1InitMeta get_initMetaObj()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnRewardTimeout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1StageController : ActivityStageController
{
	private Act5D1InitMeta m_initMetaObj; // 0x60
	private static DelegateBridge __Hotfix0_get_staticActivityId; // 0x0
	private static DelegateBridge __Hotfix0_get_initMetaObj; // 0x8
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x10
	private static DelegateBridge __Hotfix0_OnRewardTimeout; // 0x18
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public static String staticActivityId { get; }
	public Act5D1InitMeta initMetaObj { get; }

	// RVA: 0x31c362c VA: 0x75957db62c
	public static String get_staticActivityId() { }
	// RVA: 0x31c5c7c VA: 0x75957ddc7c
	public Act5D1InitMeta get_initMetaObj() { }
	// RVA: 0x31c5d3c VA: 0x75957ddd3c
	protected override Void OnStageTimeout() { }
	// RVA: 0x31c5f1c VA: 0x75957ddf1c
	protected override Void OnRewardTimeout() { }
	// RVA: 0x31c60fc VA: 0x75957de0fc
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x31c61d4 VA: 0x75957de1d4
	public Void .ctor() { }
	// RVA: 0x31c6244 VA: 0x75957de244
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x31c624c VA: 0x75957de24c
	private Void <>xLuaBaseProxy_OnRewardTimeout() { }
}
```