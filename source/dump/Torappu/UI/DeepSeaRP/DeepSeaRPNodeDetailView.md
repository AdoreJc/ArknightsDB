# DeepSeaRPNodeDetailView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `Text _textTitle`

- `GameObject _arrowGo`

- `GameObject _btnLeaveGo`

- `GameObject _btnActionGo`

- `UIAtlasObject _detailAtlas`

- `GameObject _commonIconGo`

- `UIAtlasImage _imgNodeIcon`

- `UIAtlasImage _imgDeco`

- `AVGTypeWriterText _typewriter`

- `Text _textDesc`

- `GameObject _additionBlockGo`

- `Image _imgNodePic`

- `Image _imgSpecialPic`

- `UIAnimationLocation _enterAnim`

- `GameObject _storyViewGo`

- `Text _textReadStory`

- `UIAnimationLocation _storyEnterAnim`

- `GameObject _chestViewGo`

- `UIAnimationLocation _chestEnterAnim`

- `AVGTypeWriterText _chestTypewriter`

- `Text _textChestDes`

- `Text _textChestConfirm`

- `GameObject _btnChestLeaveGo`

- `GameObject _btnChestConfirmGo`

- `GameObject _btnChestAlreadyGo`

- `Color _completeItemColor`

- `GameObject _completeMaskGo`

- `Text _textMissionDesc`

- `Color _colorMissionIncomplete`

- `Color _colorMissionComplete`

- `GameObject _rewardListGo`

- `SimpleLayoutContent _chestRewardList`

- `Single _rewardItemScale`

- `GameObject _choiceViewGo`

- `UIAnimationLocation _choiceEnterAnim`

- `SimpleLayoutContent _choiceList`

- `ChoiceListAdapter m_choiceListAdapter`

- `MissionRewardListAdapter m_rewardListAdapter`

- `Boolean m_hasInited`

- `Int32 m_originFontSize`

- `AutoPackSpriteHub m_specialPicHub`

- `AutoPackSpriteHub m_nodePicHub`

- `String m_actId`

- `IntroStep <status>k__BackingField`

- `Action <onBtnLeave>k__BackingField`


## Properties

- `IntroStep status`

- `Action onBtnLeave`


## Methods

- `IntroStep get_status()`

- `Void set_status(IntroStep)`

- `Void set_onChoiceItemSelected(Action`2)`

- `Action get_onBtnLeave()`

- `Void set_onBtnLeave(Action)`

- `Void HideAdditionViews()`

- `Void PlayEnterAnim(Action)`

- `Void UpdateSpecialPic(String)`

- `Void UpdateNodePic(String)`

- `Void InitView()`

- `Void _InitIfNot()`

- `Void RenderStaticView(String, DeepSeaRPNodeModel, EventData)`

- `Void ClearDesc()`

- `Void StopTyping()`

- `Sprite _LoadSpecialPic(String)`

- `Sprite _LoadNodePic(String)`

- `Sprite _LoadPicFromAutoSpriteHub(AutoPackSpriteHub, String)`

- `Void _PrepareFontSize(Text, String)`

- `Int32 _BinaryFind(Text, String)`

- `Boolean _CheckSuitable(Text, String, Int32, Vector2)`

- `IEnumerator IntroCoroutine(DeepSeaRPNodeModel, EventData, Boolean)`

- `IEnumerator _ShowAdditionViewCoroutine(DeepSeaRPNodeModel, String)`

- `IEnumerator _ShowChoiceCoroutine(DeepSeaRPNodeModel)`

- `Void _UpdateChoiceView(DeepSeaRPChoiceModel)`

- `IEnumerator _ShowTechCoroutine(DeepSeaRPNodeModel, String)`

- `Void _UpdateTechView(DeepSeaRPTechNodeModel)`

- `IEnumerator _ShowTreasureCoroutine(DeepSeaRPNodeModel, String)`

- `Void _UpdateTresureView(DeepSeaRPTreasureNodeModel)`

- `IEnumerator _ShowStoryCoroutine(DeepSeaRPNodeModel)`

- `Void _UpdateStoryView(DeepSeaRPStoryNodeModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPNodeDetailView : MonoBehaviour, IHotfixable
{
	private Text _textTitle; // 0x18
	private GameObject _arrowGo; // 0x20
	private GameObject _btnLeaveGo; // 0x28
	private GameObject _btnActionGo; // 0x30
	private UIAtlasObject _detailAtlas; // 0x38
	private GameObject _commonIconGo; // 0x40
	private UIAtlasImage _imgNodeIcon; // 0x48
	private UIAtlasImage _imgDeco; // 0x50
	private AVGTypeWriterText _typewriter; // 0x58
	private Text _textDesc; // 0x60
	private GameObject _additionBlockGo; // 0x68
	private Image _imgNodePic; // 0x70
	private Image _imgSpecialPic; // 0x78
	private UIAnimationLocation _enterAnim; // 0x80
	private GameObject _storyViewGo; // 0x90
	private Text _textReadStory; // 0x98
	private UIAnimationLocation _storyEnterAnim; // 0xa0
	private GameObject _chestViewGo; // 0xb0
	private UIAnimationLocation _chestEnterAnim; // 0xb8
	private AVGTypeWriterText _chestTypewriter; // 0xc8
	private Text _textChestDes; // 0xd0
	private Text _textChestConfirm; // 0xd8
	private GameObject _btnChestLeaveGo; // 0xe0
	private GameObject _btnChestConfirmGo; // 0xe8
	private GameObject _btnChestAlreadyGo; // 0xf0
	private Color _completeItemColor; // 0xf8
	private GameObject _completeMaskGo; // 0x108
	private Text _textMissionDesc; // 0x110
	private Color _colorMissionIncomplete; // 0x118
	private Color _colorMissionComplete; // 0x128
	private GameObject _rewardListGo; // 0x138
	private SimpleLayoutContent _chestRewardList; // 0x140
	private Single _rewardItemScale; // 0x148
	private GameObject _choiceViewGo; // 0x150
	private UIAnimationLocation _choiceEnterAnim; // 0x158
	private SimpleLayoutContent _choiceList; // 0x168
	private ChoiceListAdapter m_choiceListAdapter; // 0x170
	private MissionRewardListAdapter m_rewardListAdapter; // 0x178
	private Boolean m_hasInited; // 0x180
	private Int32 m_originFontSize; // 0x184
	private AutoPackSpriteHub m_specialPicHub; // 0x188
	private AutoPackSpriteHub m_nodePicHub; // 0x190
	private String m_actId; // 0x198
	private IntroStep <status>k__BackingField; // 0x1a0
	private Action`2 <onChoiceItemSelected>k__BackingField; // 0x1a8
	private Action <onBtnLeave>k__BackingField; // 0x1b0
	private static DelegateBridge __Hotfix0_get_status; // 0x0
	private static DelegateBridge __Hotfix0_set_status; // 0x8
	private static DelegateBridge __Hotfix0_get_onChoiceItemSelected; // 0x10
	private static DelegateBridge __Hotfix0_set_onChoiceItemSelected; // 0x18
	private static DelegateBridge __Hotfix0_get_onBtnLeave; // 0x20
	private static DelegateBridge __Hotfix0_set_onBtnLeave; // 0x28
	private static DelegateBridge __Hotfix0_HideAdditionViews; // 0x30
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x38
	private static DelegateBridge __Hotfix0_UpdateSpecialPic; // 0x40
	private static DelegateBridge __Hotfix0_UpdateNodePic; // 0x48
	private static DelegateBridge __Hotfix0_InitView; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0_RenderStaticView; // 0x60
	private static DelegateBridge __Hotfix0_ClearDesc; // 0x68
	private static DelegateBridge __Hotfix0_StopTyping; // 0x70
	private static DelegateBridge __Hotfix0__LoadSpecialPic; // 0x78
	private static DelegateBridge __Hotfix0__LoadNodePic; // 0x80
	private static DelegateBridge __Hotfix0__LoadPicFromAutoSpriteHub; // 0x88
	private static DelegateBridge __Hotfix0__PrepareFontSize; // 0x90
	private static DelegateBridge __Hotfix0__BinaryFind; // 0x98
	private static DelegateBridge __Hotfix0__CheckSuitable; // 0xa0
	private static DelegateBridge __Hotfix0_IntroCoroutine; // 0xa8
	private static DelegateBridge __Hotfix0__ShowAdditionViewCoroutine; // 0xb0
	private static DelegateBridge __Hotfix0__ShowChoiceCoroutine; // 0xb8
	private static DelegateBridge __Hotfix0__UpdateChoiceView; // 0xc0
	private static DelegateBridge __Hotfix0__ShowTechCoroutine; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateTechView; // 0xd0
	private static DelegateBridge __Hotfix0__ShowTreasureCoroutine; // 0xd8
	private static DelegateBridge __Hotfix0__UpdateTresureView; // 0xe0
	private static DelegateBridge __Hotfix0__ShowStoryCoroutine; // 0xe8
	private static DelegateBridge __Hotfix0__UpdateStoryView; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8

	public IntroStep status { get; set; }
	private Action`2 onChoiceItemSelected { get; set; }
	private Action onBtnLeave { get; set; }

	// RVA: 0x29db060 VA: 0x7594ff3060
	public IntroStep get_status() { }
	// RVA: 0x29db0c8 VA: 0x7594ff30c8
	public Void set_status(IntroStep value) { }
	// RVA: 0x29dc8f4 VA: 0x7594ff48f4
	private Action`2 get_onChoiceItemSelected() { }
	// RVA: 0x29da45c VA: 0x7594ff245c
	public Void set_onChoiceItemSelected(Action`2 value) { }
	// RVA: 0x29dc95c VA: 0x7594ff495c
	private Action get_onBtnLeave() { }
	// RVA: 0x29da4e0 VA: 0x7594ff24e0
	public Void set_onBtnLeave(Action value) { }
	// RVA: 0x29db144 VA: 0x7594ff3144
	public Void HideAdditionViews() { }
	// RVA: 0x29daafc VA: 0x7594ff2afc
	public Void PlayEnterAnim(Action onComplete) { }
	// RVA: 0x29dc368 VA: 0x7594ff4368
	public Void UpdateSpecialPic(String specialPicId) { }
	// RVA: 0x29dc46c VA: 0x7594ff446c
	public Void UpdateNodePic(String nodePicId) { }
	// RVA: 0x29da564 VA: 0x7594ff2564
	public Void InitView() { }
	// RVA: 0x29dcbf4 VA: 0x7594ff4bf4
	private Void _InitIfNot() { }
	// RVA: 0x29da604 VA: 0x7594ff2604
	public Void RenderStaticView(String actId, DeepSeaRPNodeModel nodeModel, EventData lockedEventData) { }
	// RVA: 0x29da98c VA: 0x7594ff298c
	public Void ClearDesc() { }
	// RVA: 0x29db4e4 VA: 0x7594ff34e4
	public Void StopTyping() { }
	// RVA: 0x29dc9c4 VA: 0x7594ff49c4
	private Sprite _LoadSpecialPic(String picId) { }
	// RVA: 0x29dcadc VA: 0x7594ff4adc
	private Sprite _LoadNodePic(String picId) { }
	// RVA: 0x29dcc80 VA: 0x7594ff4c80
	private Sprite _LoadPicFromAutoSpriteHub(AutoPackSpriteHub spriteHub, String picId) { }
	// RVA: 0x29dce08 VA: 0x7594ff4e08
	private Void _PrepareFontSize(Text textComp, String desc) { }
	// RVA: 0x29dcef4 VA: 0x7594ff4ef4
	private Int32 _BinaryFind(Text textComp, String desc) { }
	// RVA: 0x29dd040 VA: 0x7594ff5040
	private Boolean _CheckSuitable(Text textComp, String desc, Int32 fontSize, Vector2 extents) { }
	// RVA: 0x29dc174 VA: 0x7594ff4174
	public IEnumerator IntroCoroutine(DeepSeaRPNodeModel nodeModel, EventData eventData, Boolean showAdditionView) { }
	// RVA: 0x29dd354 VA: 0x7594ff5354
	private IEnumerator _ShowAdditionViewCoroutine(DeepSeaRPNodeModel nodeModel, String desc) { }
	// RVA: 0x29dd43c VA: 0x7594ff543c
	private IEnumerator _ShowChoiceCoroutine(DeepSeaRPNodeModel nodeModel) { }
	// RVA: 0x29dd50c VA: 0x7594ff550c
	private Void _UpdateChoiceView(DeepSeaRPChoiceModel choiceModel) { }
	// RVA: 0x29dd648 VA: 0x7594ff5648
	private IEnumerator _ShowTechCoroutine(DeepSeaRPNodeModel nodeModel, String desc) { }
	// RVA: 0x29dd730 VA: 0x7594ff5730
	private Void _UpdateTechView(DeepSeaRPTechNodeModel techModel) { }
	// RVA: 0x29dd9b0 VA: 0x7594ff59b0
	private IEnumerator _ShowTreasureCoroutine(DeepSeaRPNodeModel nodeModel, String desc) { }
	// RVA: 0x29dda98 VA: 0x7594ff5a98
	private Void _UpdateTresureView(DeepSeaRPTreasureNodeModel treasureModel) { }
	// RVA: 0x29dddd0 VA: 0x7594ff5dd0
	private IEnumerator _ShowStoryCoroutine(DeepSeaRPNodeModel nodeModel) { }
	// RVA: 0x29ddea0 VA: 0x7594ff5ea0
	private Void _UpdateStoryView(DeepSeaRPStoryNodeModel storyModel) { }
	// RVA: 0x29ddf40 VA: 0x7594ff5f40
	public Void .ctor() { }
}
```