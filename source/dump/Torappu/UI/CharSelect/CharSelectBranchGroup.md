# CharSelectBranchGroup

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `Transform _talentContainer`

- `GameObject _contentItemPrefab`

- `Text _subProfName`

- `UICommentedText _subProfDetailBasic`

- `UICommentedText _subProfDetailAdditive`

- `Image _subProfImg`

- `GameObject _panelUniequip`

- `SimpleLayoutContent _branchLayout`

- `UIStringEvent _onBranchSelected`

- `BranchAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderView(CharSelectBranchGroupViewModel)`

- `Void _OnBranchSelected(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectBranchGroup : MonoBehaviour, IHotfixable
{
	private Transform _talentContainer; // 0x18
	private GameObject _contentItemPrefab; // 0x20
	private Text _subProfName; // 0x28
	private UICommentedText _subProfDetailBasic; // 0x30
	private UICommentedText _subProfDetailAdditive; // 0x38
	private Image _subProfImg; // 0x40
	private GameObject _panelUniequip; // 0x48
	private SimpleLayoutContent _branchLayout; // 0x50
	private UIStringEvent _onBranchSelected; // 0x58
	private CharacterTalentViewModel[] m_talentsCache; // 0x60
	private BranchAdapter m_adapter; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0__OnBranchSelected; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2cf467c VA: 0x759530c67c
	private Void _InitIfNot() { }
	// RVA: 0x2cf3ca8 VA: 0x759530bca8
	public Void RenderView(CharSelectBranchGroupViewModel branchModel) { }
	// RVA: 0x2cf4800 VA: 0x759530c800
	private Void _OnBranchSelected(String equipId) { }
	// RVA: 0x2cf48ac VA: 0x759530c8ac
	public Void .ctor() { }
}
```