# ItemRepoUseChangeNameCard

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Text _currentNameText`

- `Text _changeNameText`

- `InputField _inputText`

- `ChangeNameNotifyView _notifyView`

- `UnityEvent _dismissAction`

- `Text _title`

- `GameObject _onTimePart`

- `Text _onTimeText`

- `String m_changeName`

- `String m_itemId`

- `Int32 m_instId`


## Methods

- `Void RenderChangeName(UIItemViewModel)`

- `Void OnEndEditText(String)`

- `Void OnClickConfirm()`

- `Void _BindNickNameServiceSuccess(UseRenameCardResponse)`

- `Void Dismiss()`

- `Void <_BindNickNameServiceSuccess>b__14_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoUseChangeNameCard : MonoBehaviour, IHotfixable
{
	private Text _currentNameText; // 0x18
	private Text _changeNameText; // 0x20
	private InputField _inputText; // 0x28
	private ChangeNameNotifyView _notifyView; // 0x30
	private UnityEvent _dismissAction; // 0x38
	private Text _title; // 0x40
	private GameObject _onTimePart; // 0x48
	private Text _onTimeText; // 0x50
	private String m_changeName; // 0x58
	private String m_itemId; // 0x60
	private Int32 m_instId; // 0x68
	private static DelegateBridge __Hotfix0_RenderChangeName; // 0x0
	private static DelegateBridge __Hotfix0_OnEndEditText; // 0x8
	private static DelegateBridge __Hotfix0_OnClickConfirm; // 0x10
	private static DelegateBridge __Hotfix0__BindNickNameServiceSuccess; // 0x18
	private static DelegateBridge __Hotfix0_Dismiss; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d3aadc VA: 0x7595352adc
	public Void RenderChangeName(UIItemViewModel itemViewModel) { }
	// RVA: 0x2d3af20 VA: 0x7595352f20
	public Void OnEndEditText(String text) { }
	// RVA: 0x2d3b05c VA: 0x759535305c
	public Void OnClickConfirm() { }
	// RVA: 0x2d3b2d0 VA: 0x75953532d0
	private Void _BindNickNameServiceSuccess(UseRenameCardResponse response) { }
	// RVA: 0x2d3b3a0 VA: 0x75953533a0
	public Void Dismiss() { }
	// RVA: 0x2d3b41c VA: 0x759535341c
	public Void .ctor() { }
	// RVA: 0x2d3b48c VA: 0x759535348c
	private Void <_BindNickNameServiceSuccess>b__14_0() { }
}
```