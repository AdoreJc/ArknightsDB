# MusicHomeThemeDiscRightView

**Namespace:** ` `


## Fields

- `RectTransform _transformDiscRight`

- `Int32 _discRightDefaultX`

- `Int32 _discRightTargetX`

- `Single _transDuration`

- `ArchiveMusicListDataBinder <closure>k__BackingField`

- `Sequence m_seqOut`

- `Sequence m_seqIn`

- `Sequence m_seqToggle`

- `Boolean m_isSwitching`


## Properties

- `ArchiveMusicListDataBinder closure`


## Methods

- `ArchiveMusicListDataBinder get_closure()`

- `Void set_closure(ArchiveMusicListDataBinder)`

- `Void _KillIfNecessary(ref)`

- `Void BeforeSwitchAnim()`

- `Void AfterSwitchAnim()`

- `Void OnHomeThemeChanged()`

- `Void ResetPosition()`

- `Void <BeforeSwitchAnim>b__13_0()`

- `Void <AfterSwitchAnim>b__14_0()`

- `Void <OnHomeThemeChanged>b__15_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MusicHomeThemeDiscRightView : IHotfixable
{
	private RectTransform _transformDiscRight; // 0x10
	private Int32 _discRightDefaultX; // 0x18
	private Int32 _discRightTargetX; // 0x1c
	private Single _transDuration; // 0x20
	private ArchiveMusicListDataBinder <closure>k__BackingField; // 0x28
	private Sequence m_seqOut; // 0x30
	private Sequence m_seqIn; // 0x38
	private Sequence m_seqToggle; // 0x40
	private Boolean m_isSwitching; // 0x48
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0__KillIfNecessary; // 0x10
	private static DelegateBridge __Hotfix0_BeforeSwitchAnim; // 0x18
	private static DelegateBridge __Hotfix0_AfterSwitchAnim; // 0x20
	private static DelegateBridge __Hotfix0_OnHomeThemeChanged; // 0x28
	private static DelegateBridge __Hotfix0_ResetPosition; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ArchiveMusicListDataBinder closure { get; set; }

	// RVA: 0x3060d48 VA: 0x7595678d48
	private ArchiveMusicListDataBinder get_closure() { }
	// RVA: 0x305edc4 VA: 0x7595676dc4
	public Void set_closure(ArchiveMusicListDataBinder value) { }
	// RVA: 0x3060db0 VA: 0x7595678db0
	private Void _KillIfNecessary(ref Sequence seq) { }
	// RVA: 0x305fc08 VA: 0x7595677c08
	public Void BeforeSwitchAnim() { }
	// RVA: 0x305fe50 VA: 0x7595677e50
	public Void AfterSwitchAnim() { }
	// RVA: 0x305f2fc VA: 0x75956772fc
	public Void OnHomeThemeChanged() { }
	// RVA: 0x305f0b0 VA: 0x75956770b0
	public Void ResetPosition() { }
	// RVA: 0x3060ec4 VA: 0x7595678ec4
	public Void .ctor() { }
	// RVA: 0x3060f34 VA: 0x7595678f34
	private Void <BeforeSwitchAnim>b__13_0() { }
	// RVA: 0x3060f60 VA: 0x7595678f60
	private Void <AfterSwitchAnim>b__14_0() { }
	// RVA: 0x3060f8c VA: 0x7595678f8c
	private Void <OnHomeThemeChanged>b__15_0() { }
}
```