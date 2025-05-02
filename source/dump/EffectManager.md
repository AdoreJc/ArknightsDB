# EffectManager

**Namespace:** ` `


## Fields

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void PlayEffectAtUtilChar(String, Character)`

- `Void PlayEffectAtTile(String, GridPosition)`

- `Void PlayLinkedEffect(String, GridPosition, GridPosition, Vector3)`

- `Void PlayEffectInfoIfNot(EffectInfoViewModel, Vector3)`

- `Boolean TryGetEffectId(String, out)`

- `Void _ClearAllEffect(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EffectManager : IHotfixable
{
	private ObjectPtr`1 m_upgradeUtilTrap; // 0x10
	private Boolean m_inited; // 0x20
	public ListDict`2 effectHolder; // 0x28
	private static DelegateBridge __Hotfix0_get_upgradeUtilTrap; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_PlayEffectAtUtilChar; // 0x10
	private static DelegateBridge __Hotfix0_PlayEffectAtTile; // 0x18
	private static DelegateBridge __Hotfix0_PlayLinkedEffect; // 0x20
	private static DelegateBridge __Hotfix0_PlayEffectInfoIfNot; // 0x28
	private static DelegateBridge __Hotfix0_TryGetEffectId; // 0x30
	private static DelegateBridge __Hotfix0__ClearAllEffect; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private ObjectPtr`1 upgradeUtilTrap { get; }

	// RVA: 0x1ca82d4 VA: 0x75942c02d4
	private ObjectPtr`1 get_upgradeUtilTrap() { }
	// RVA: 0x1ca86dc VA: 0x75942c06dc
	private Void _InitIfNot() { }
	// RVA: 0x1ca8804 VA: 0x75942c0804
	public Void PlayEffectAtUtilChar(String effectKey, Character character) { }
	// RVA: 0x1ca8c24 VA: 0x75942c0c24
	public Void PlayEffectAtTile(String effectKey, GridPosition pos) { }
	// RVA: 0x1ca8fcc VA: 0x75942c0fcc
	public Void PlayLinkedEffect(String effectKey, GridPosition source, GridPosition target, Vector3 shopCenterWorldPos) { }
	// RVA: 0x1ca9508 VA: 0x75942c1508
	public Void PlayEffectInfoIfNot(EffectInfoViewModel viewModel, Vector3 shopCenterWorldPos) { }
	// RVA: 0x1ca8af4 VA: 0x75942c0af4
	private Boolean TryGetEffectId(String effectKey, out SceneEffectSetting effectId) { }
	// RVA: 0x1ca9a64 VA: 0x75942c1a64
	private Void _ClearAllEffect(Object arg) { }
	// RVA: 0x1ca9d88 VA: 0x75942c1d88
	public Void .ctor() { }
}
```