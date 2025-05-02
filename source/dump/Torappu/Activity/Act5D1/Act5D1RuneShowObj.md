# Act5D1RuneShowObj

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

- `GameObject _runeUnlockCannotBuy`

- `Image _backImage`


## Methods

- `Void ApplyData(String, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneShowObj : MonoBehaviour, IHotfixable
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
	private GameObject _runeUnlockCannotBuy; // 0x60
	private Image _backImage; // 0x68
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x31c9b58 VA: 0x75957e1b58
	public Void ApplyData(String stageId, String runeId, Boolean canUnlock) { }
	// RVA: 0x31c9e74 VA: 0x75957e1e74
	public Void .ctor() { }
}
```