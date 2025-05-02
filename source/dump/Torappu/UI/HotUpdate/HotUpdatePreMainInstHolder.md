# HotUpdatePreMainInstHolder

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Transform _transform`

- `HotUpdatePreMainView m_preMainView`

- `Assets m_assets`

- `HotUpdatePreMainProperty m_property`

- `IContext m_context`


## Methods

- `Void InitView(IContext)`

- `Void _TryInstPreMainView(HotUpdateViewProp)`

- `Void ClearViewIfNotNull(HotUpdateViewProp)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdatePreMainInstHolder : DataBinder`1
{
	private Transform _transform; // 0x20
	private HotUpdatePreMainView m_preMainView; // 0x28
	private Assets m_assets; // 0x30
	private HotUpdatePreMainProperty m_property; // 0x38
	private IContext m_context; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_InitView; // 0x8
	private static DelegateBridge __Hotfix0__TryInstPreMainView; // 0x10
	private static DelegateBridge __Hotfix0_ClearViewIfNotNull; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x27cb0f4 VA: 0x7594de30f4
	public override Void OnValueChanged(HotUpdateViewProp property) { }
	// RVA: 0x27bcd0c VA: 0x7594dd4d0c
	public Void InitView(IContext context) { }
	// RVA: 0x27cb1a4 VA: 0x7594de31a4
	private Void _TryInstPreMainView(HotUpdateViewProp property) { }
	// RVA: 0x27bd30c VA: 0x7594dd530c
	public Void ClearViewIfNotNull(HotUpdateViewProp property) { }
	// RVA: 0x27cb644 VA: 0x7594de3644
	public Void .ctor() { }
}
```