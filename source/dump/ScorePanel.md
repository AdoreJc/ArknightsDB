# ScorePanel

**Namespace:** ` `


## Fields

- `CrisisV2DiagramView _diagramItemPrefab`

- `Transform _diagramHolder`

- `Text _txtScore`

- `Image _imgAppraise`

- `GameObject _objNewScoreTag`

- `GameObject _objCommentParent`

- `SimpleLayoutContent _commentLayoutLeft`

- `SimpleLayoutContent _commentLayoutRight`

- `UIAnimationLocation _animScoreEnter`

- `UIAnimationLocation _animScoreNew`

- `UIAnimationLocation _animScoreResult`

- `CommentAdapter m_adapterLeft`

- `CommentAdapter m_adapterRight`

- `Tween m_tweener`

- `CrisisV2DiagramView m_diagramItem`

- `Boolean m_hasInited`


## Methods

- `Void Render(CrisisV2SettleViewModel, ILoadAsset)`

- `Void RenderNewScoreDiagram(CrisisV2SettleViewModel)`

- `Void HidePanel()`

- `Void PlayScoreEnterAnim(TweenCallback)`

- `Void PlayScoreNewAnim(TweenCallback)`

- `Void PlayScoreResultAnim(TweenCallback)`

- `Void Reset()`

- `Void _InitIfNot()`

- `Void _SetPanelObjVisable(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ScorePanel : IHotfixable
{
	private CrisisV2DiagramView _diagramItemPrefab; // 0x10
	private Transform _diagramHolder; // 0x18
	private Text _txtScore; // 0x20
	private Image _imgAppraise; // 0x28
	private GameObject _objNewScoreTag; // 0x30
	private GameObject _objCommentParent; // 0x38
	private SimpleLayoutContent _commentLayoutLeft; // 0x40
	private SimpleLayoutContent _commentLayoutRight; // 0x48
	private UIAnimationLocation _animScoreEnter; // 0x50
	private UIAnimationLocation _animScoreNew; // 0x60
	private UIAnimationLocation _animScoreResult; // 0x70
	private List`1 _objScores; // 0x80
	private CommentAdapter m_adapterLeft; // 0x88
	private CommentAdapter m_adapterRight; // 0x90
	private Tween m_tweener; // 0x98
	private CrisisV2DiagramView m_diagramItem; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RenderNewScoreDiagram; // 0x8
	private static DelegateBridge __Hotfix0_HidePanel; // 0x10
	private static DelegateBridge __Hotfix0_PlayScoreEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0_PlayScoreNewAnim; // 0x20
	private static DelegateBridge __Hotfix0_PlayScoreResultAnim; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__SetPanelObjVisable; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2bd2724 VA: 0x75951ea724
	public Void Render(CrisisV2SettleViewModel viewModel, ILoadAsset loader) { }
	// RVA: 0x2bd2c10 VA: 0x75951eac10
	public Void RenderNewScoreDiagram(CrisisV2SettleViewModel viewModel) { }
	// RVA: 0x2bd2d28 VA: 0x75951ead28
	public Void HidePanel() { }
	// RVA: 0x2bd2d94 VA: 0x75951ead94
	public Void PlayScoreEnterAnim(TweenCallback onScoreEnterPlayFinish) { }
	// RVA: 0x2bd2e28 VA: 0x75951eae28
	public Void PlayScoreNewAnim(TweenCallback onScoreNewPlayFinish) { }
	// RVA: 0x2bd2ebc VA: 0x75951eaebc
	public Void PlayScoreResultAnim(TweenCallback onScoreResultPlayFinish) { }
	// RVA: 0x2bd16dc VA: 0x75951e96dc
	public Void Reset() { }
	// RVA: 0x2bd2974 VA: 0x75951ea974
	private Void _InitIfNot() { }
	// RVA: 0x2bd2b24 VA: 0x75951eab24
	private Void _SetPanelObjVisable(Boolean show) { }
	// RVA: 0x2bd2fb0 VA: 0x75951eafb0
	public Void .ctor() { }
}
```