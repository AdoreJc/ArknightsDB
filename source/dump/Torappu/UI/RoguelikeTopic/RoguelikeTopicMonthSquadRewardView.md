# RoguelikeTopicMonthSquadRewardView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `SimpleLayoutContent _rewardList`

- `Text _textBpPointCount`

- `Image _iconBpPoint`

- `Image _imgReceivedLight`

- `Image _imgBpCountBg`

- `Text _textReceiveBpDesc`

- `Text _textBpMax`

- `GameObject _fullPart`

- `GameObject _normalPart`

- `CanvasGroup _canvasBp`

- `CanvasGroup _canvasItems`

- `GameObject _pnlAwardReceived`

- `Adapter m_listAdapter`

- `Input m_cachedInput`

- `String m_cachedTopicId`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Input)`

- `Void _RenderTopic(String, Input)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthSquadRewardView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _rewardList; // 0x18
	private Text _textBpPointCount; // 0x20
	private Image _iconBpPoint; // 0x28
	private Image _imgReceivedLight; // 0x30
	private Image _imgBpCountBg; // 0x38
	private Text _textReceiveBpDesc; // 0x40
	private Text _textBpMax; // 0x48
	private GameObject _fullPart; // 0x50
	private GameObject _normalPart; // 0x58
	private CanvasGroup _canvasBp; // 0x60
	private CanvasGroup _canvasItems; // 0x68
	private GameObject _pnlAwardReceived; // 0x70
	private Adapter m_listAdapter; // 0x78
	private Input m_cachedInput; // 0x80
	private String m_cachedTopicId; // 0x88
	private Boolean m_hasInited; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderTopic; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2656b3c VA: 0x7594c6eb3c
	private Void _InitIfNot() { }
	// RVA: 0x265672c VA: 0x7594c6e72c
	public Void Render(Input input) { }
	// RVA: 0x2656ca0 VA: 0x7594c6eca0
	private Void _RenderTopic(String topicId, Input input) { }
	// RVA: 0x2656f38 VA: 0x7594c6ef38
	public Void .ctor() { }
}
```