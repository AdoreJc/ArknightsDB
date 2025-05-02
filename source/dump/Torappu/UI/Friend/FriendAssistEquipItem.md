# FriendAssistEquipItem

**Namespace:** `Torappu.UI.Friend`


## Fields

- `UICommonEquipTypeIcon _equipIconPrefab`

- `Transform _equipIconContainer`

- `Single _equipIconScale`

- `Single _unselectAlpha`

- `Button _pressButton`

- `GameObject _iconPanel`

- `GameObject _slectedPanel`

- `GameObject _noneEquipPanel`

- `GameObject _lockEquipPanel`

- `Text _textLevel`

- `GameObject _panelText`

- `GameObject _hotspot`

- `String m_cachedEquipId`

- `UICommonEquipTypeIcon m_equipIcon`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot(Single)`

- `Void Render(String, String, RenderOptions)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistEquipItem : MonoBehaviour, IHotfixable
{
	private UICommonEquipTypeIcon _equipIconPrefab; // 0x18
	private Transform _equipIconContainer; // 0x20
	private Single _equipIconScale; // 0x28
	private Single _unselectAlpha; // 0x2c
	private Button _pressButton; // 0x30
	private GameObject _iconPanel; // 0x38
	private GameObject _slectedPanel; // 0x40
	private GameObject _noneEquipPanel; // 0x48
	private GameObject _lockEquipPanel; // 0x50
	private Text _textLevel; // 0x58
	private GameObject _panelText; // 0x60
	private GameObject _hotspot; // 0x68
	public Action`2 onItemClicked; // 0x70
	private String m_cachedEquipId; // 0x78
	private UICommonEquipTypeIcon m_equipIcon; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28c7f94 VA: 0x7594edff94
	private Void _InitIfNot(Single parentScale) { }
	// RVA: 0x28c8138 VA: 0x7594ee0138
	public Void Render(String equipId, String charId, RenderOptions options) { }
	// RVA: 0x28c83dc VA: 0x7594ee03dc
	public Void OnClick() { }
	// RVA: 0x28c8468 VA: 0x7594ee0468
	public Void .ctor() { }
}
```