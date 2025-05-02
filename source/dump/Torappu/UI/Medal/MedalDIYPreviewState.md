# MedalDIYPreviewState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `RectTransform _container`

- `MedalDIYPreviewBean m_stateBean`

- `UIMedalGroupView m_groupView`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalDIYPreviewState : PopupFloatState
{
	private RectTransform _container; // 0x70
	private MedalDIYPreviewBean m_stateBean; // 0x78
	private UIMedalGroupView m_groupView; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x27656e0 VA: 0x7594d7d6e0
	private Void _InitIfNot() { }
	// RVA: 0x27657e0 VA: 0x7594d7d7e0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2765848 VA: 0x7594d7d848
	protected override Void OnEnter() { }
	// RVA: 0x2765a74 VA: 0x7594d7da74
	public Void .ctor() { }
	// RVA: 0x2765b20 VA: 0x7594d7db20
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```