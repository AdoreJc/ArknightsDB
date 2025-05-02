# Act5D1RuneShowSelectObj

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Text _runeName`

- `Image _runeIcon`

- `Text _runePoint`

- `Text _runeDetail`

- `Text _runeDescription`

- `Text _runeLockedInfo`

- `GameObject _runeLocked`

- `GameObject _pointPart`

- `GameObject _newHandPoint`

- `GameObject _isSelectedPart`

- `GameObject _isBanned`

- `GameObject _isNotAvailable`

- `GameObject _isAbleToUnlock`

- `Button _clickBtn`

- `UIStringEvent clickEvent`

- `Image _backImage`

- `String m_cacheRuneId`


## Methods

- `Void Click()`

- `Void ApplyData(RuneInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneShowSelectObj : MonoBehaviour, IHotfixable
{
	private Text _runeName; // 0x18
	private Image _runeIcon; // 0x20
	private Text _runePoint; // 0x28
	private Text _runeDetail; // 0x30
	private Text _runeDescription; // 0x38
	private Text _runeLockedInfo; // 0x40
	private GameObject _runeLocked; // 0x48
	private GameObject _pointPart; // 0x50
	private GameObject _newHandPoint; // 0x58
	private GameObject _isSelectedPart; // 0x60
	private GameObject _isBanned; // 0x68
	private GameObject _isNotAvailable; // 0x70
	private GameObject _isAbleToUnlock; // 0x78
	private Button _clickBtn; // 0x80
	public UIStringEvent clickEvent; // 0x88
	private Image _backImage; // 0x90
	private String m_cacheRuneId; // 0x98
	private static DelegateBridge __Hotfix0_Click; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31c9ee4 VA: 0x75957e1ee4
	public Void Click() { }
	// RVA: 0x31c9f94 VA: 0x75957e1f94
	public Void ApplyData(RuneInfo runeInput) { }
	// RVA: 0x31ca2b4 VA: 0x75957e22b4
	public Void .ctor() { }
}
```