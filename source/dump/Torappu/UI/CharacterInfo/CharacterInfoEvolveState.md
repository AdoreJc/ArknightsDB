# CharacterInfoEvolveState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoEvolveStateBean _stateBean`

- `Text _nameInConfirmInfo`

- `Transform _panelIllustOld`

- `Transform _panelIllustNew`

- `Material _illustSilhouetteMat`

- `Color _illustSilhouetteColor`

- `Single _illustScaleFactor`

- `CharacterInfoEvolveAttrController _panelUpgradeAttrs`

- `SimpleLayoutContent _requireLayout`

- `CharacterEvolveTextContainer _evolveText`

- `CharacterEvolveDetailView _detailView`

- `GameObject _guidebookTrigger`

- `Animator _animAll`

- `CanvasGroup _alphaListener`

- `Boolean m_animDetailOpen`

- `Boolean m_animStateEnter`

- `UICharacterIllust m_illustOld`

- `UICharacterIllust m_illustNew`


## Methods

- `Void OnDestroy()`

- `Void _RefreshPlayerStatusViews()`

- `Void OnDetailClick()`

- `Void OnBackClick()`

- `Void OnUpgradeConfirmClick()`

- `Void OnUpgradeCancelClick()`

- `Void _BindBackPressListeners()`

- `Void _ClearIllusts()`

- `Void _UpdateAnimatorStates()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoEvolveState : UIPopupState
{
	private const String ANIM_DETAIL_OPEN_KEY; // 0x0
	private const String ANIM_STATE_ENTER_KEY; // 0x0
	private const String ANIM_STATE_FAST_KEY; // 0x0
	private CharacterInfoEvolveStateBean _stateBean; // 0x60
	private Text _nameInConfirmInfo; // 0x68
	private Transform _panelIllustOld; // 0x70
	private Transform _panelIllustNew; // 0x78
	private Material _illustSilhouetteMat; // 0x80
	private Color _illustSilhouetteColor; // 0x88
	private Single _illustScaleFactor; // 0x98
	private CharacterInfoEvolveAttrController _panelUpgradeAttrs; // 0xa0
	private SimpleLayoutContent _requireLayout; // 0xa8
	private CharacterEvolveTextContainer _evolveText; // 0xb0
	private CharacterEvolveDetailView _detailView; // 0xb8
	private GameObject _guidebookTrigger; // 0xc0
	private Animator _animAll; // 0xc8
	private CanvasGroup _alphaListener; // 0xd0
	private Boolean m_animDetailOpen; // 0xd8
	private Boolean m_animStateEnter; // 0xd9
	private UICharacterIllust m_illustOld; // 0xe0
	private UICharacterIllust m_illustNew; // 0xe8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__RefreshPlayerStatusViews; // 0x20
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x28
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x30
	private static DelegateBridge __Hotfix0_OnUpgradeConfirmClick; // 0x38
	private static DelegateBridge __Hotfix0_OnUpgradeCancelClick; // 0x40
	private static DelegateBridge __Hotfix0__BindBackPressListeners; // 0x48
	private static DelegateBridge __Hotfix0__ClearIllusts; // 0x50
	private static DelegateBridge __Hotfix0__UpdateAnimatorStates; // 0x58
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x68
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x70
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x2d3e608 VA: 0x7595356608
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d3e670 VA: 0x7595356670
	protected override Void OnEnter() { }
	// RVA: 0x2d3edcc VA: 0x7595356dcc
	protected override Void OnResume() { }
	// RVA: 0x2d3ef54 VA: 0x7595356f54
	protected Void OnDestroy() { }
	// RVA: 0x2d3ec70 VA: 0x7595356c70
	private Void _RefreshPlayerStatusViews() { }
	// RVA: 0x2d3f050 VA: 0x7595357050
	public Void OnDetailClick() { }
	// RVA: 0x2d3f138 VA: 0x7595357138
	public Void OnBackClick() { }
	// RVA: 0x2d3f21c VA: 0x759535721c
	public Void OnUpgradeConfirmClick() { }
	// RVA: 0x2d3f4dc VA: 0x75953574dc
	public Void OnUpgradeCancelClick() { }
	// RVA: 0x2d3e964 VA: 0x7595356964
	private Void _BindBackPressListeners() { }
	// RVA: 0x2d3eb48 VA: 0x7595356b48
	private Void _ClearIllusts() { }
	// RVA: 0x2d3ee98 VA: 0x7595356e98
	private Void _UpdateAnimatorStates() { }
	// RVA: 0x2d3f568 VA: 0x7595357568
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2d3f6e0 VA: 0x75953576e0
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2d3f858 VA: 0x7595357858
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2d3f974 VA: 0x7595357974
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2d3fa8c VA: 0x7595357a8c
	public Void .ctor() { }
	// RVA: 0x2d3fb14 VA: 0x7595357b14
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d3fb1c VA: 0x7595357b1c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```