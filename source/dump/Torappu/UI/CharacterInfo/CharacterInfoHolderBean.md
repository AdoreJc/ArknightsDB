# CharacterInfoHolderBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharInfoGroupProperty _property`


## Properties

- `CultivateViewModel currentFocusCultivateViewModel`

- `CharViewModel currentFocusCharViewModel`

- `CharInfoGroupProperty property`


## Methods

- `CultivateViewModel get_currentFocusCultivateViewModel()`

- `CharViewModel get_currentFocusCharViewModel()`

- `CharInfoGroupProperty get_property()`

- `Void InitData(ICharInfoHomeInitParam)`

- `Void SetFocus(Int32)`

- `Void RefreshInstId(Int32)`

- `Void RefreshCurrentFocus()`

- `Void ClearData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoHolderBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private CharInfoGroupProperty _property; // 0x18
	private static DelegateBridge __Hotfix0_get_currentFocusCultivateViewModel; // 0x0
	private static DelegateBridge __Hotfix0_get_currentFocusCharViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_property; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x18
	private static DelegateBridge __Hotfix0_SetFocus; // 0x20
	private static DelegateBridge __Hotfix0_RefreshInstId; // 0x28
	private static DelegateBridge __Hotfix0_RefreshCurrentFocus; // 0x30
	private static DelegateBridge __Hotfix0_ClearData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public CultivateViewModel currentFocusCultivateViewModel { get; }
	public CharViewModel currentFocusCharViewModel { get; }
	public CharInfoGroupProperty property { get; }

	// RVA: 0x2d543b0 VA: 0x759536c3b0
	public CultivateViewModel get_currentFocusCultivateViewModel() { }
	// RVA: 0x2d545c8 VA: 0x759536c5c8
	public CharViewModel get_currentFocusCharViewModel() { }
	// RVA: 0x2d54450 VA: 0x759536c450
	public CharInfoGroupProperty get_property() { }
	// RVA: 0x2d5465c VA: 0x759536c65c
	public Void InitData(ICharInfoHomeInitParam param) { }
	// RVA: 0x2d549bc VA: 0x759536c9bc
	public Void SetFocus(Int32 focusIndex) { }
	// RVA: 0x2d54afc VA: 0x759536cafc
	public Void RefreshInstId(Int32 instId) { }
	// RVA: 0x2d54cec VA: 0x759536ccec
	public Void RefreshCurrentFocus() { }
	// RVA: 0x2d54da4 VA: 0x759536cda4
	public Void ClearData() { }
	// RVA: 0x2d54e60 VA: 0x759536ce60
	public Void .ctor() { }
}
```