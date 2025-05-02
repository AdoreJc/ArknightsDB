# CharacterInfoRightLevelView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _preferHeight`

- `Text _currentLevel`

- `Text _maxLevel`

- `Image _expBar`

- `Text _expBarCurrent`

- `Text _expBarLimit`

- `Image plusImg`

- `Image maxImg`


## Methods

- `Void Render(CharViewModel)`

- `Void <>xLuaBaseProxy_AllHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightLevelView : CharacterInfoCommonObj, IHotfixable
{
	private Single _preferHeight; // 0x2c
	private Text _currentLevel; // 0x30
	private Text _maxLevel; // 0x38
	private Image _expBar; // 0x40
	private Text _expBarCurrent; // 0x48
	private Text _expBarLimit; // 0x50
	private Image plusImg; // 0x58
	private Image maxImg; // 0x60
	private static DelegateBridge __Hotfix0_AllHide; // 0x0
	private static DelegateBridge __Hotfix0_GetHeight; // 0x8
	private static DelegateBridge __Hotfix0_ApplyViewModel; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d82530 VA: 0x759539a530
	public override Void AllHide() { }
	// RVA: 0x2d82598 VA: 0x759539a598
	public override Single GetHeight() { }
	// RVA: 0x2d82600 VA: 0x759539a600
	public override Void ApplyViewModel(CharViewModel charViewModel) { }
	// RVA: 0x2d82680 VA: 0x759539a680
	public Void Render(CharViewModel charViewModel) { }
	// RVA: 0x2d8286c VA: 0x759539a86c
	public Void .ctor() { }
	// RVA: 0x2d828d8 VA: 0x759539a8d8
	private Void <>xLuaBaseProxy_AllHide() { }
}
```