# LpeoplFearHudPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIFollowSlider _fearSlider`

- `GameObject _fullFearUI`

- `GameObject _fullNotFearUI`

- `Image _icon`

- `LpeoplFearHudPluginTalent m_hudTalent`


## Methods

- `Void Update()`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class LpeoplFearHudPlugin : UnitTalentUIPlugin
{
	private UIFollowSlider _fearSlider; // 0x30
	private GameObject _fullFearUI; // 0x38
	private GameObject _fullNotFearUI; // 0x40
	private Image _icon; // 0x48
	private LpeoplFearHudPluginTalent m_hudTalent; // 0x50
	private const Single initAlpha; // 0x0
	private const Single deltaAlpha; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x201a8c0 VA: 0x75946328c0
	protected override Void DoAttach(Unit owner, UIPluginTalent uiTalent) { }
	// RVA: 0x201a9d8 VA: 0x75946329d8
	private Void Update() { }
	// RVA: 0x201ac24 VA: 0x7594632c24
	public Void .ctor() { }
	// RVA: 0x201ac94 VA: 0x7594632c94
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
}
```