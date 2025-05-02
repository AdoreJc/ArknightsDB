# RoguelikeDiceView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeDiceGroup _diceScenePrefab`

- `UIAnimationLocation _uiAnim`

- `Font _numFont`

- `Text _diceNum`

- `Image _resultTag`

- `GameObject _rerollBtn`

- `GameObject _rerollBtnHot`

- `Text _rerollCount`

- `Transform _resultInfoRoot`

- `Vector2 _renderTextureSize`

- `RoguelikeEventRawImage _bg`

- `Action onCheckBtnClick`

- `Action onRerollBtnClick`

- `RoguelikeDiceGroup m_dice`

- `RoguelikeDiceResultViewBase m_resultView`

- `RenderTexture m_rt`


## Methods

- `Void InitIfNot(Transform)`

- `Void OnDestroy()`

- `RoguelikeDicePlugin GetPluginPrefab(Type)`

- `Void EventOnCheck()`

- `Void EventOnReroll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDiceView : DataBinder`1
{
	private RoguelikeDicePlugin[] _definedPlugins; // 0x20
	private RoguelikeDiceResultViewBase[] _definedResultViews; // 0x28
	private ResultClassImage[] _resultSprites; // 0x30
	private RoguelikeDiceGroup _diceScenePrefab; // 0x38
	private UIAnimationLocation _uiAnim; // 0x40
	private Font _numFont; // 0x50
	private Text _diceNum; // 0x58
	private Image _resultTag; // 0x60
	private GameObject _rerollBtn; // 0x68
	private GameObject _rerollBtnHot; // 0x70
	private Text _rerollCount; // 0x78
	private Transform _resultInfoRoot; // 0x80
	private Vector2 _renderTextureSize; // 0x88
	private RoguelikeEventRawImage _bg; // 0x90
	public Action onCheckBtnClick; // 0x98
	public Action onRerollBtnClick; // 0xa0
	private RoguelikeDiceGroup m_dice; // 0xa8
	private RoguelikeDiceResultViewBase m_resultView; // 0xb0
	private RenderTexture m_rt; // 0xb8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_GetPluginPrefab; // 0x18
	private static DelegateBridge __Hotfix0_GetSupportedResultViewModelCreators; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCheck; // 0x28
	private static DelegateBridge __Hotfix0_EventOnReroll; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x29f948c VA: 0x759501148c
	public Void InitIfNot(Transform diceSceneRoot) { }
	// RVA: 0x29fa750 VA: 0x7595012750
	private Void OnDestroy() { }
	// RVA: 0x29fa800 VA: 0x7595012800
	public override Void OnValueChanged(RoguelikeDiceModelProperty property) { }
	// RVA: 0x29f963c VA: 0x759501163c
	public RoguelikeDicePlugin GetPluginPrefab(Type typeOfPlugin) { }
	// RVA: 0x29f97e4 VA: 0x75950117e4
	public Dictionary`2 GetSupportedResultViewModelCreators() { }
	// RVA: 0x29faedc VA: 0x7595012edc
	public Void EventOnCheck() { }
	// RVA: 0x29faf60 VA: 0x7595012f60
	public Void EventOnReroll() { }
	// RVA: 0x29fb000 VA: 0x7595013000
	public Void .ctor() { }
}
```