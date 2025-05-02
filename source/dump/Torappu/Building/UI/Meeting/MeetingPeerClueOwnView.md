# MeetingPeerClueOwnView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Int32 _category`

- `Text _numberLabel`

- `GameObject _ownPanel`

- `GameObject _canHelpPanel`

- `GameObject _canNotHelpPanel`


## Properties

- `Int32 category`


## Methods

- `Int32 get_category()`

- `Void Awake()`

- `Void Setup(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingPeerClueOwnView : MonoBehaviour, IHotfixable
{
	public Int32 _category; // 0x18
	public Text _numberLabel; // 0x20
	public GameObject _ownPanel; // 0x28
	public GameObject _canHelpPanel; // 0x30
	public GameObject _canNotHelpPanel; // 0x38
	private static DelegateBridge __Hotfix0_get_category; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0_Setup; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Int32 category { get; }

	// RVA: 0x3dfdcc0 VA: 0x7596415cc0
	public Int32 get_category() { }
	// RVA: 0x3dfdd28 VA: 0x7596415d28
	private Void Awake() { }
	// RVA: 0x3dfddb8 VA: 0x7596415db8
	public Void Setup(Boolean peerOwnClue, Boolean selfOwnClue) { }
	// RVA: 0x3dfde70 VA: 0x7596415e70
	public Void .ctor() { }
}
```