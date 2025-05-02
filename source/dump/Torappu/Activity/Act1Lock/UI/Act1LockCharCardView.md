# Act1LockCharCardView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `UIAtlasImage _portrait`

- `Text _levelTxt`

- `Image _evolveImg`

- `Image _potentialImg`

- `Image _rarityBackImg`

- `Image _professionImg`

- `GameObject _noPart`

- `GameObject _availPart`

- `String m_portrait`


## Methods

- `Void Clear()`

- `Void FillNo()`

- `Void Fill(CharacterCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockCharCardView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _portrait; // 0x18
	private Text _levelTxt; // 0x20
	private Image _evolveImg; // 0x28
	private Image _potentialImg; // 0x30
	private Sprite[] _rarityBackSprite; // 0x38
	private Image _rarityBackImg; // 0x40
	private Image _professionImg; // 0x48
	private GameObject _noPart; // 0x50
	private GameObject _availPart; // 0x58
	private String m_portrait; // 0x60
	private static DelegateBridge __Hotfix0_Clear; // 0x0
	private static DelegateBridge __Hotfix0_FillNo; // 0x8
	private static DelegateBridge __Hotfix0_Fill; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x33a910c VA: 0x75959c110c
	public Void Clear() { }
	// RVA: 0x33a9190 VA: 0x75959c1190
	public Void FillNo() { }
	// RVA: 0x33a9218 VA: 0x75959c1218
	public Void Fill(CharacterCardViewModel cardViewModel) { }
	// RVA: 0x33a9500 VA: 0x75959c1500
	public Void .ctor() { }
}
```