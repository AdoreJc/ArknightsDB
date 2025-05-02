# NameCardSkinChangeView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Text _skinNameText`

- `Text _skinNameBottomText`

- `Text _skinDescText`

- `GameObject _lockIcon`

- `NameCardSkinListAdapter _skinListAdapter`

- `Button _confirmBtn`

- `GameObject _disableConfirmObj`

- `GameObject _buttonGroup`

- `Int32 m_focusSkinListSeqNum`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinChangeView : DataBinder`1
{
	private const String UNLCOK_CONDITION_TYPE; // 0x0
	private const Int32 CURRENT_PROGRESS_IDX; // 0x0
	private const Int32 MAX_PROGRESS_IDX; // 0x0
	private Text _skinNameText; // 0x20
	private Text _skinNameBottomText; // 0x28
	private Text _skinDescText; // 0x30
	private GameObject _lockIcon; // 0x38
	private NameCardSkinListAdapter _skinListAdapter; // 0x40
	private Button _confirmBtn; // 0x48
	private GameObject _disableConfirmObj; // 0x50
	private GameObject _buttonGroup; // 0x58
	private Int32 m_focusSkinListSeqNum; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x28dcd08 VA: 0x7594ef4d08
	public override Void OnValueChanged(NameCardSkinChangeProperty property) { }
	// RVA: 0x28dd23c VA: 0x7594ef523c
	public Void .ctor() { }
}
```