# OpenServerV2MissionItem

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Text _txtContent`

- `Text _txtItem`

- `Image _imgItem`

- `Text _txtItemCount`

- `Text _txtMissionProcess`

- `RectTransform _fullProcessBar`

- `RectTransform _processBar`

- `GameObject _panelNotComplete`

- `GameObject _panelAvailable`

- `GameObject _panelAlreadyGot`

- `CanvasGroup _canvasGroupRight`

- `UIAnimationLocation _animationLocation`

- `UIStateFinder m_stateFinder`

- `String m_missionId`

- `Tween m_tween`


## Methods

- `Void Render(Int32, OpenServerV2MissionItemData)`

- `Void OnClick()`

- `Void _OnMissionItemClick()`

- `Void _RenderMissionState(MissionPlayerState)`

- `Void <OnClick>b__16_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2MissionItem : MonoBehaviour, IHotfixable
{
	private Text _txtContent; // 0x18
	private Text _txtItem; // 0x20
	private Image _imgItem; // 0x28
	private Text _txtItemCount; // 0x30
	private Text _txtMissionProcess; // 0x38
	private RectTransform _fullProcessBar; // 0x40
	private RectTransform _processBar; // 0x48
	private GameObject _panelNotComplete; // 0x50
	private GameObject _panelAvailable; // 0x58
	private GameObject _panelAlreadyGot; // 0x60
	private CanvasGroup _canvasGroupRight; // 0x68
	private UIAnimationLocation _animationLocation; // 0x70
	private UIStateFinder m_stateFinder; // 0x80
	private String m_missionId; // 0x90
	private Tween m_tween; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__OnMissionItemClick; // 0x10
	private static DelegateBridge __Hotfix0__RenderMissionState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28560ac VA: 0x7594e6e0ac
	public Void Render(Int32 index, OpenServerV2MissionItemData missionItemData) { }
	// RVA: 0x285661c VA: 0x7594e6e61c
	public Void OnClick() { }
	// RVA: 0x2856790 VA: 0x7594e6e790
	private Void _OnMissionItemClick() { }
	// RVA: 0x28563b8 VA: 0x7594e6e3b8
	private Void _RenderMissionState(MissionPlayerState missionPlayerState) { }
	// RVA: 0x2856898 VA: 0x7594e6e898
	public Void .ctor() { }
	// RVA: 0x2856908 VA: 0x7594e6e908
	private Void <OnClick>b__16_0() { }
}
```