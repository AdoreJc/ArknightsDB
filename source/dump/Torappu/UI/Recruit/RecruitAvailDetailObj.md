# RecruitAvailDetailObj

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Image _rarityImg`

- `Text _upTxt`

- `Text _availChar`

- `GameObject _endLine`

- `GameObject _holder6StarHint`

- `Text _text6StarHintLabel`


## Methods

- `Void Render(GachaPerAvail, Boolean, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitAvailDetailObj : MonoBehaviour, IHotfixable
{
	private Image _rarityImg; // 0x18
	private Text _upTxt; // 0x20
	private Text _availChar; // 0x28
	private GameObject _endLine; // 0x30
	private GameObject _holder6StarHint; // 0x38
	private Text _text6StarHintLabel; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x270f7dc VA: 0x7594d277dc
	public Void Render(GachaPerAvail perObj, Boolean isEnd, String recruit6StarHint) { }
	// RVA: 0x270fbf0 VA: 0x7594d27bf0
	public Void .ctor() { }
}
```