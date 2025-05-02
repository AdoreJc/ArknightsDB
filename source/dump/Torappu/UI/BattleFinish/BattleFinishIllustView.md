# BattleFinishIllustView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `Transform _illustContainer`

- `Transform _illustTextContainer`

- `Text _illustText`

- `String m_illustString`

- `UICharacterIllust m_illust`

- `Boolean m_isCurCharValid`


## Methods

- `Void Start()`

- `Void Render(BattleInfoViewModel)`

- `String _ProcessCharWordLineSplitting_LetterBase(String, Int32)`

- `String _ProcessCharWordLineSplitting_WordBase(String, Int32)`

- `IEnumerator _UpdateWord()`

- `IEnumerator _UpdateLayout(RectTransform)`

- `Void _UpdateIllustTextDisplayStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishIllustView : MonoBehaviour, IHotfixable
{
	private Transform _illustContainer; // 0x18
	private Transform _illustTextContainer; // 0x20
	private Text _illustText; // 0x28
	private String m_illustString; // 0x30
	private const Int32 MAXFRAME; // 0x0
	private UICharacterIllust m_illust; // 0x38
	private Boolean m_isCurCharValid; // 0x40
	private const String CHARWORDFORMAT; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__ProcessCharWordLineSplitting_LetterBase; // 0x10
	private static DelegateBridge __Hotfix0__ProcessCharWordLineSplitting_WordBase; // 0x18
	private static DelegateBridge __Hotfix0__UpdateWord; // 0x20
	private static DelegateBridge __Hotfix0__UpdateLayout; // 0x28
	private static DelegateBridge __Hotfix0__UpdateIllustTextDisplayStatus; // 0x30
	private static DelegateBridge __Hotfix0__SelectProperCharWord; // 0x38
	private static DelegateBridge __Hotfix0__ShowWhichCharWord; // 0x40
	private static DelegateBridge __Hotfix0__CheckIsPassOrCompleted; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2e91a44 VA: 0x75954a9a44
	private Void Start() { }
	// RVA: 0x2e8f4c4 VA: 0x75954a74c4
	public Void Render(BattleInfoViewModel battleInfoModel) { }
	// RVA: 0x2e91d80 VA: 0x75954a9d80
	private String _ProcessCharWordLineSplitting_LetterBase(String content, Int32 maxLength) { }
	// RVA: 0x2e91efc VA: 0x75954a9efc
	private String _ProcessCharWordLineSplitting_WordBase(String content, Int32 maxLength) { }
	// RVA: 0x2e91cd4 VA: 0x75954a9cd4
	private IEnumerator _UpdateWord() { }
	// RVA: 0x2e921c0 VA: 0x75954aa1c0
	private IEnumerator _UpdateLayout(RectTransform rect) { }
	// RVA: 0x2e91aac VA: 0x75954a9aac
	private Void _UpdateIllustTextDisplayStatus() { }
	// RVA: 0x2e91b74 VA: 0x75954a9b74
	private static CharWordData _SelectProperCharWord(CharUISkinStruct skin, BattleInfoViewModel battleInfoModel) { }
	// RVA: 0x2e922a8 VA: 0x75954aa2a8
	private static CharWordShowType _ShowWhichCharWord(BattleInfoViewModel battleInfoModel) { }
	// RVA: 0x2e92354 VA: 0x75954aa354
	private static CharWordShowType _CheckIsPassOrCompleted(BattleInfoViewModel battleInfoModel) { }
	// RVA: 0x2e9240c VA: 0x75954aa40c
	public Void .ctor() { }
}
```