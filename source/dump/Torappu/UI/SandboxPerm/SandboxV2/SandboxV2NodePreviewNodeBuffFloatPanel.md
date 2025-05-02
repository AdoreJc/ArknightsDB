# SandboxV2NodePreviewNodeBuffFloatPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _detailAlphaHandler`

- `RectTransform _detailPositionHandler`

- `Vector2 _detailShowPos`

- `Vector2 _detailHidePos`

- `Text _nameText`

- `Text _descText`

- `Text _extraText`

- `Boolean m_hasInited`

- `UISwitchTween m_detailShowTween`


## Methods

- `Void _InitIfNot()`

- `Void Render(SandboxV2DungeonNodeBuffViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewNodeBuffFloatPanel : SandboxV2FloatPanel
{
	private CanvasGroup _detailAlphaHandler; // 0x30
	private RectTransform _detailPositionHandler; // 0x38
	private Vector2 _detailShowPos; // 0x40
	private Vector2 _detailHidePos; // 0x48
	private Text _nameText; // 0x50
	private Text _descText; // 0x58
	private Text _extraText; // 0x60
	private Boolean m_hasInited; // 0x68
	private UISwitchTween m_detailShowTween; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x256d778 VA: 0x7594b85778
	private Void _InitIfNot() { }
	// RVA: 0x256d8ac VA: 0x7594b858ac
	protected override Void SetShowStatus(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x256d95c VA: 0x7594b8595c
	public Void Render(SandboxV2DungeonNodeBuffViewModel buffViewModel) { }
	// RVA: 0x256da3c VA: 0x7594b85a3c
	public Void .ctor() { }
}
```