# RecruitFesClassicCharPortObj

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RectTransform _container`

- `RecruitCharDetailObj _charObj`

- `RecruitUpCharDetailPortraitObj _portraitObj`

- `Text _title`

- `Image _starIcon`

- `GameObject _endLine`

- `GridLayoutGroup _containerLayoutGroup`


## Methods

- `Void Render(JArrayWrapper, RarityRank, String, Boolean, Boolean, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitFesClassicCharPortObj : MonoBehaviour, IHotfixable
{
	private const Single CHAR_PORT_CELL_HEIGHT; // 0x0
	private const Single CHAR_CELL_HEIGHT; // 0x0
	private const Int32 CHAR_PORT_ROW_CELL_COUNT; // 0x0
	private const Int32 CHAR_ROW_CELL_COUNT; // 0x0
	private const Single CHAR_PORT_SCALE_SIZE; // 0x0
	private const Single CHAR_SCALE_SIZE; // 0x0
	private RectTransform _container; // 0x18
	private RecruitCharDetailObj _charObj; // 0x20
	private RecruitUpCharDetailPortraitObj _portraitObj; // 0x28
	private Text _title; // 0x30
	private Image _starIcon; // 0x38
	private GameObject _endLine; // 0x40
	private GridLayoutGroup _containerLayoutGroup; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2710abc VA: 0x7594d28abc
	public Void Render(JArrayWrapper upCharIdList, RarityRank rarityRank, String titleText, Boolean isEnd, Boolean isPortrait, List`1 limitList) { }
	// RVA: 0x2710e2c VA: 0x7594d28e2c
	public Void .ctor() { }
}
```