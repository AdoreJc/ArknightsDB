# ZoneRecordRewardItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Image _icon`

- `GameObject _isAvailable`

- `GameObject _isGained`

- `GameObject _missionIcon`

- `SimpleLayoutContent _rewardItemsContent`

- `GameObject _splitLine`

- `CanvasGroup _canvasGroup`

- `Single _scaleFactor`

- `RectTransform _rectFinishPart`

- `RectTransform _rectAvailPart`

- `Boolean m_isInited`

- `Single m_defaultFinishRectHeigh`

- `Single m_defaultAvailRectHeigh`


## Methods

- `Void _InitIfNot()`

- `Void Render(Int32, ZoneRecordRewardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordRewardItemView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _isAvailable; // 0x20
	private GameObject _isGained; // 0x28
	private GameObject _missionIcon; // 0x30
	private SimpleLayoutContent _rewardItemsContent; // 0x38
	private GameObject _splitLine; // 0x40
	private CanvasGroup _canvasGroup; // 0x48
	private Single _scaleFactor; // 0x50
	private RectTransform _rectFinishPart; // 0x58
	private RectTransform _rectAvailPart; // 0x60
	private Boolean m_isInited; // 0x68
	private Single m_defaultFinishRectHeigh; // 0x6c
	private Single m_defaultAvailRectHeigh; // 0x70
	private const Single COLOR_ALPHA_ONE; // 0x0
	private const Single COLOR_ALPHA_HALF; // 0x0
	private const Single CLAIM_FLAG_CEIL_WIDTH; // 0x0
	private const Single AVAIL_CLAIM_FLAG_ADD_WIDTH; // 0x0
	private const Single REWARDS_LONG_LIMIT; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__GenRewardViewModel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fc2200 VA: 0x75955da200
	private Void _InitIfNot() { }
	// RVA: 0x2fc22a0 VA: 0x75955da2a0
	public Void Render(Int32 idx, ZoneRecordRewardViewModel rewardViewModel) { }
	// RVA: 0x2fc2748 VA: 0x75955da748
	private List`1 _GenRewardViewModel(ItemBundle[] items) { }
	// RVA: 0x2fc291c VA: 0x75955da91c
	public Void .ctor() { }
}
```