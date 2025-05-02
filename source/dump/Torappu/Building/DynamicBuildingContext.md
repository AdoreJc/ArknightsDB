# DynamicBuildingContext

**Namespace:** `Torappu.Building`


## Fields

- `Int32 m_refCount`

- `Content m_content`

- `Boolean m_isInitRetain`


## Properties

- `BuildingModel model`

- `BuildingServiceController service`

- `Boolean isEmpty`


## Methods

- `Int64 GetInstSignature()`

- `Void Retain()`

- `Void Release()`

- `Void Clear()`

- `Void UpdateTime(Single)`

- `BuildingModel get_model()`

- `BuildingServiceController get_service()`

- `Boolean get_isEmpty()`

- `Void _CreateInst()`

- `Void <Retain>b__5_0(Scene, Scene)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class DynamicBuildingContext : IBuildingContext, IHotfixable, ITimeWatcher, IRefCountInstance
{
	private Int32 m_refCount; // 0x10
	private Content m_content; // 0x18
	private Boolean m_isInitRetain; // 0x28
	private static DelegateBridge __Hotfix0_GetInstSignature; // 0x0
	private static DelegateBridge __Hotfix0_Retain; // 0x8
	private static DelegateBridge __Hotfix0_Release; // 0x10
	private static DelegateBridge __Hotfix0_Clear; // 0x18
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x20
	private static DelegateBridge __Hotfix0_get_model; // 0x28
	private static DelegateBridge __Hotfix0_get_service; // 0x30
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x38
	private static DelegateBridge __Hotfix0__CreateInst; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public BuildingModel model { get; }
	public BuildingServiceController service { get; }
	public Boolean isEmpty { get; }

	// RVA: 0x3777404 VA: 0x7595d8f404
	public Int64 GetInstSignature() { }
	// RVA: 0x377747c VA: 0x7595d8f47c
	public Void Retain() { }
	// RVA: 0x3777760 VA: 0x7595d8f760
	public Void Release() { }
	// RVA: 0x37777e8 VA: 0x7595d8f7e8
	public Void Clear() { }
	// RVA: 0x377789c VA: 0x7595d8f89c
	public Void UpdateTime(Single delta) { }
	// RVA: 0x3777930 VA: 0x7595d8f930
	public BuildingModel get_model() { }
	// RVA: 0x3777998 VA: 0x7595d8f998
	public BuildingServiceController get_service() { }
	// RVA: 0x3777a00 VA: 0x7595d8fa00
	public Boolean get_isEmpty() { }
	// RVA: 0x3777588 VA: 0x7595d8f588
	private Void _CreateInst() { }
	// RVA: 0x3777ac4 VA: 0x7595d8fac4
	public Void .ctor() { }
	// RVA: 0x3777b7c VA: 0x7595d8fb7c
	private Void <Retain>b__5_0(Scene from, Scene to) { }
}
```