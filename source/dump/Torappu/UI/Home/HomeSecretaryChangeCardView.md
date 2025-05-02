# HomeSecretaryChangeCardView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _headIcon`

- `GameObject _objNotSelected`

- `GameObject _objStarMark`

- `Text _selectedSkinNum`

- `GameObject _objInPreview`

- `Int32 m_instId`

- `BasicCharInfoModel m_charInfoModel`


## Properties

- `BasicCharInfoModel basicCharInfo`


## Methods

- `BasicCharInfoModel get_basicCharInfo()`

- `Void RenderCard(HomeSecretaryCardViewModel, ExtraInput)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretaryChangeCardView : MonoBehaviour, IBasicCharInfo, IHotfixable
{
	private Image _headIcon; // 0x18
	private GameObject _objNotSelected; // 0x20
	private GameObject[] _objListSelected; // 0x28
	private GameObject _objStarMark; // 0x30
	private Text _selectedSkinNum; // 0x38
	private GameObject _objInPreview; // 0x40
	private Int32 m_instId; // 0x48
	private BasicCharInfoModel m_charInfoModel; // 0x50
	public Action`1 onClick; // 0x58
	private static DelegateBridge __Hotfix0_get_basicCharInfo; // 0x0
	private static DelegateBridge __Hotfix0_RenderCard; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public BasicCharInfoModel basicCharInfo { get; }

	// RVA: 0x283cdbc VA: 0x7594e54dbc
	public BasicCharInfoModel get_basicCharInfo() { }
	// RVA: 0x283ce24 VA: 0x7594e54e24
	public Void RenderCard(HomeSecretaryCardViewModel cardModel, ExtraInput input) { }
	// RVA: 0x283d088 VA: 0x7594e55088
	public Void OnClick() { }
	// RVA: 0x283d110 VA: 0x7594e55110
	public Void .ctor() { }
}
```