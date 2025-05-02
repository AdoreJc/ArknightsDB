# HomeCharRotationPresetItemModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `String presetInstId`

- `String presetName`

- `String profileSkinId`

- `String nowPreviewingSkinId`

- `String backgroundId`

- `String themeId`

- `String musicId`


## Methods

- `Void LoadDataByPlayerPreset(PlayerCharRotationPreset, String)`

- `Void RefreshProfileSkinId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationPresetItemModel : IHotfixable
{
	public String presetInstId; // 0x10
	public String presetName; // 0x18
	public String profileSkinId; // 0x20
	public String nowPreviewingSkinId; // 0x28
	public String backgroundId; // 0x30
	public String themeId; // 0x38
	public String musicId; // 0x40
	public ListDict`2 presetSkins; // 0x48
	private Dictionary`2 m_charSkinCount; // 0x50
	private static DelegateBridge __Hotfix0_LoadDataByPlayerPreset; // 0x0
	private static DelegateBridge __Hotfix0_RefreshProfileSkinId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x280c188 VA: 0x7594e24188
	public Void LoadDataByPlayerPreset(PlayerCharRotationPreset preset, String instId) { }
	// RVA: 0x280c668 VA: 0x7594e24668
	public Void RefreshProfileSkinId() { }
	// RVA: 0x280c848 VA: 0x7594e24848
	public Void .ctor() { }
}
```