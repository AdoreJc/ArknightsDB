# ClimbTowerLayerMenuButton

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `CanvasGroup _canvasCurr`

- `CanvasGroup _canvasBack`

- `Text _textDesc`

- `UIAtlasImage _imgBtnBkg`

- `UIAtlasObject _atlasObject`

- `String _normalBkgId`

- `String _hardBkgId`

- `SwitchTween m_switchTween`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLayerMenuButton : ClimbTowerMenuButton
{
	private CanvasGroup _canvasCurr; // 0x20
	private CanvasGroup _canvasBack; // 0x28
	private Text _textDesc; // 0x30
	private UIAtlasImage _imgBtnBkg; // 0x38
	private UIAtlasObject _atlasObject; // 0x40
	private String _normalBkgId; // 0x48
	private String _hardBkgId; // 0x50
	private SwitchTween m_switchTween; // 0x58
	private Boolean m_hasInited; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c80714 VA: 0x7595298714
	private Void _InitIfNot() { }
	// RVA: 0x2c80878 VA: 0x7595298878
	public override Void Render(IClimbTowerMenuButtonDataSource dataSource, Boolean fastMode) { }
	// RVA: 0x2c80a54 VA: 0x7595298a54
	public Void .ctor() { }
}
```