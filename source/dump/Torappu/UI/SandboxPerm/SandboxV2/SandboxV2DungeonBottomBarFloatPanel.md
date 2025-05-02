# SandboxV2DungeonBottomBarFloatPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _detailAlphaHandler`

- `RectTransform _detailPositionHandler`

- `Vector2 _detailShowPos`

- `Vector2 _detailHidePos`

- `GameObject _pnlArchive`

- `GameObject _pnlArchiveText`

- `GameObject _pnlArchiveCoolDown`

- `Text _countDownText`

- `CanvasGroup _archiveCg`

- `Single _archiveCoolDownAlpha`

- `GameObject _archiveHotspot`

- `GameObject _pnlDelete`

- `GameObject _pnlDeleteDiv`

- `Boolean m_inited`

- `UISwitchTween m_detailShowTween`

- `CountDownTask m_cacheCountDownTask`

- `SandboxV2DungeonViewModel m_cachedDungeonViewModel`


## Methods

- `Void Update()`

- `Void Render(SandboxV2DungeonViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonBottomBarFloatPanel : SandboxV2FloatPanel
{
	private CanvasGroup _detailAlphaHandler; // 0x30
	private RectTransform _detailPositionHandler; // 0x38
	private Vector2 _detailShowPos; // 0x40
	private Vector2 _detailHidePos; // 0x48
	private GameObject _pnlArchive; // 0x50
	private GameObject _pnlArchiveText; // 0x58
	private GameObject _pnlArchiveCoolDown; // 0x60
	private Text _countDownText; // 0x68
	private CanvasGroup _archiveCg; // 0x70
	private Single _archiveCoolDownAlpha; // 0x78
	private GameObject _archiveHotspot; // 0x80
	private GameObject _pnlDelete; // 0x88
	private GameObject _pnlDeleteDiv; // 0x90
	private Boolean m_inited; // 0x98
	private UISwitchTween m_detailShowTween; // 0xa0
	private CountDownTask m_cacheCountDownTask; // 0xa8
	private SandboxV2DungeonViewModel m_cachedDungeonViewModel; // 0xb0
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x255cb64 VA: 0x7594b74b64
	private Void Update() { }
	// RVA: 0x255c6d8 VA: 0x7594b746d8
	public Void Render(SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x255cbe8 VA: 0x7594b74be8
	private Void _InitIfNot() { }
	// RVA: 0x255cd1c VA: 0x7594b74d1c
	protected override Void SetShowStatus(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x255cdcc VA: 0x7594b74dcc
	public Void .ctor() { }
}
```