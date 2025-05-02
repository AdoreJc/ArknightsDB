# ClimbTowerInitStepListAdapter

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 m_stepCount`

- `Int32 m_currentStep`


## Methods

- `Void LoadData(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitStepListAdapter : SimpleLayoutAdapter
{
	private Int32 m_stepCount; // 0x20
	private Int32 m_currentStep; // 0x24
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2ca87a0 VA: 0x75952c07a0
	public Void LoadData(Int32 stepCount, Int32 currentStep) { }
	// RVA: 0x2ca8d70 VA: 0x75952c0d70
	public override Int32 get_count() { }
	// RVA: 0x2ca8dd8 VA: 0x75952c0dd8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2ca8730 VA: 0x75952c0730
	public Void .ctor() { }
}
```