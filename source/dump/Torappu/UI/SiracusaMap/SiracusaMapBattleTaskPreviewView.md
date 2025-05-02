# SiracusaMapBattleTaskPreviewView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _stageName`

- `Text _itaName`

- `Text _missionDetail`

- `Text _stageDesc`

- `Color _missionFormatColor`

- `GameObject mapTips`

- `Image previewImg`

- `Image backTips`

- `StageViewModel m_selectViewModel`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `Sprite m_mapPreviewSprite`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OpenMapTips()`

- `Void _ShotBlurredSprite()`

- `Void _OnCleanMapPreview()`

- `Void _ClearBlurSprite()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapBattleTaskPreviewView : DataBinder`1
{
	private Text _stageName; // 0x20
	private Text _itaName; // 0x28
	private Text _missionDetail; // 0x30
	private Text _stageDesc; // 0x38
	private Color _missionFormatColor; // 0x40
	public GameObject mapTips; // 0x50
	public Image previewImg; // 0x58
	public Image backTips; // 0x60
	private StageViewModel m_selectViewModel; // 0x68
	private DirectAssetLoader m_stagePreviewMapLoader; // 0x70
	private Sprite m_mapPreviewSprite; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OpenMapTips; // 0x10
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0x18
	private static DelegateBridge __Hotfix0__OnCleanMapPreview; // 0x20
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x23fec3c VA: 0x7594a16c3c
	private Void _InitIfNot() { }
	// RVA: 0x23fedac VA: 0x7594a16dac
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23ff1d4 VA: 0x7594a171d4
	public Void OpenMapTips() { }
	// RVA: 0x23ff2ac VA: 0x7594a172ac
	private Void _ShotBlurredSprite() { }
	// RVA: 0x23ff44c VA: 0x7594a1744c
	private Void _OnCleanMapPreview() { }
	// RVA: 0x23ff320 VA: 0x7594a17320
	private Void _ClearBlurSprite() { }
	// RVA: 0x23ff520 VA: 0x7594a17520
	public Void .ctor() { }
}
```