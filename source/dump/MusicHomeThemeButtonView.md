# MusicHomeThemeButtonView

**Namespace:** ` `


## Fields

- `CanvasGroup _canvasSet`

- `CanvasGroup _canvasUnset`

- `Single _transDuration`

- `ArchiveMusicListDataBinder <closure>k__BackingField`

- `Sequence m_seq`


## Properties

- `ArchiveMusicListDataBinder closure`


## Methods

- `ArchiveMusicListDataBinder get_closure()`

- `Void set_closure(ArchiveMusicListDataBinder)`

- `Void RefreshHomeThemeButton()`

- `Void OnHomeThemeChanged()`

- `Void ResetPosition()`

- `Void <OnHomeThemeChanged>b__9_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MusicHomeThemeButtonView : IHotfixable
{
	private CanvasGroup _canvasSet; // 0x10
	private CanvasGroup _canvasUnset; // 0x18
	private Single _transDuration; // 0x20
	private ArchiveMusicListDataBinder <closure>k__BackingField; // 0x28
	private Sequence m_seq; // 0x30
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0_RefreshHomeThemeButton; // 0x10
	private static DelegateBridge __Hotfix0_OnHomeThemeChanged; // 0x18
	private static DelegateBridge __Hotfix0_ResetPosition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ArchiveMusicListDataBinder closure { get; set; }

	// RVA: 0x3060fb8 VA: 0x7595678fb8
	private ArchiveMusicListDataBinder get_closure() { }
	// RVA: 0x305ee48 VA: 0x7595676e48
	public Void set_closure(ArchiveMusicListDataBinder value) { }
	// RVA: 0x305f980 VA: 0x7595677980
	public Void RefreshHomeThemeButton() { }
	// RVA: 0x305f4fc VA: 0x75956774fc
	public Void OnHomeThemeChanged() { }
	// RVA: 0x305f198 VA: 0x7595677198
	public Void ResetPosition() { }
	// RVA: 0x3061020 VA: 0x7595679020
	public Void .ctor() { }
	// RVA: 0x3061090 VA: 0x7595679090
	private Void <OnHomeThemeChanged>b__9_0() { }
}
```