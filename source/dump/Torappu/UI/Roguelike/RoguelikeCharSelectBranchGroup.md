# RoguelikeCharSelectBranchGroup

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _talentContainer`

- `GameObject _contentItemPrefab`

- `Text _subProfName`

- `UICommentedText _subProfDetailBasic`

- `UICommentedText _subProfDetailAdditive`

- `Image _subProfImg`

- `GameObject _panelUniequip`

- `GameObject _panelUnlock`

- `SimpleLayoutContent _branchLayout`

- `UIStringEvent m_onBranchSelected`

- `BranchAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderView(RoguelikeCharSelectBranchGroupViewModel, UIStringEvent)`

- `Void _OnBranchSelected(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectBranchGroup : MonoBehaviour, IHotfixable
{
	private Transform _talentContainer; // 0x18
	private GameObject _contentItemPrefab; // 0x20
	private Text _subProfName; // 0x28
	private UICommentedText _subProfDetailBasic; // 0x30
	private UICommentedText _subProfDetailAdditive; // 0x38
	private Image _subProfImg; // 0x40
	private GameObject _panelUniequip; // 0x48
	private GameObject _panelUnlock; // 0x50
	private SimpleLayoutContent _branchLayout; // 0x58
	private UIStringEvent m_onBranchSelected; // 0x60
	private RoguelikeTalentViewModel[] m_talentsCache; // 0x68
	private BranchAdapter m_adapter; // 0x70
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0__OnBranchSelected; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2acd0f8 VA: 0x75950e50f8
	private Void _InitIfNot() { }
	// RVA: 0x2acc9d8 VA: 0x75950e49d8
	public Void RenderView(RoguelikeCharSelectBranchGroupViewModel branchModel, UIStringEvent branchSelectEvent) { }
	// RVA: 0x2acd3d4 VA: 0x75950e53d4
	private Void _OnBranchSelected(String equipId) { }
	// RVA: 0x2acd480 VA: 0x75950e5480
	public Void .ctor() { }
}
```