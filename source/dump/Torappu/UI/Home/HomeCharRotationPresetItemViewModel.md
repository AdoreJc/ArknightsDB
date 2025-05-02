# HomeCharRotationPresetItemViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `String presetInstId`

- `String presetName`

- `String presetThemeId`

- `String presetThemeName`

- `String presetBackgroundId`

- `String presetBackgroundName`

- `String profileSkinId`


## Methods

- `Void LoadData(String, PlayerCharRotationPreset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationPresetItemViewModel : IHotfixable
{
	public String presetInstId; // 0x10
	public String presetName; // 0x18
	public String presetThemeId; // 0x20
	public String presetThemeName; // 0x28
	public String presetBackgroundId; // 0x30
	public String presetBackgroundName; // 0x38
	public List`1 presetSkins; // 0x40
	public String profileSkinId; // 0x48
	private Dictionary`2 m_charSkinCount; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x27e0bfc VA: 0x7594df8bfc
	public Void LoadData(String instId, PlayerCharRotationPreset playerData) { }
	// RVA: 0x27e1054 VA: 0x7594df9054
	public Void .ctor() { }
}
```