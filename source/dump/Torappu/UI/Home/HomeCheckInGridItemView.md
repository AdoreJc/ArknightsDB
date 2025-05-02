# HomeCheckInGridItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _panelCurrDay`

- `GameObject _panelSelected`

- `GameObject _panelCheckInFlag`

- `CanvasGroup _canvasCheckIn`

- `Image _itemIcon`

- `GameObject _panelCountThousand`

- `GameObject _panelCountHundred`

- `GameObject _panelCountTen`

- `GameObject _prefabParticle`

- `Transform _containerParticle`

- `Int32 m_cacheId`

- `GameObject m_effectHolder`

- `UIStateFinder m_stateFinder`


## Methods

- `Void ChangeSelect()`

- `Void Render(Int32, Int32, Int32, MonthlySignInData, Boolean, Boolean)`

- `IEnumerator _PlayTodayCheckinEffect()`

- `Void _ClearEffectIfNot()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInGridItemView : MonoBehaviour
{
	private const Single ALPHA_AFTER_CHECK_IN; // 0x0
	private const Single ALPHA_NOT_CHECK_IN; // 0x0
	private const Single DELAY_CHECKIN_TODAY_EFFECT_INTERNAL; // 0x0
	private const Int32 COUNT_THOUSAND_COUNT_LIMIT; // 0x0
	private const Int32 COUNT_HUNDRED_COUNT_LIMIT; // 0x0
	private Text[] _textIndexList; // 0x18
	private GameObject _panelCurrDay; // 0x20
	private GameObject _panelSelected; // 0x28
	private GameObject _panelCheckInFlag; // 0x30
	private CanvasGroup _canvasCheckIn; // 0x38
	private Image _itemIcon; // 0x40
	private Text[] _textCountList; // 0x48
	private GameObject _panelCountThousand; // 0x50
	private GameObject _panelCountHundred; // 0x58
	private GameObject _panelCountTen; // 0x60
	private GameObject _prefabParticle; // 0x68
	private Transform _containerParticle; // 0x70
	private Int32 m_cacheId; // 0x78
	private GameObject m_effectHolder; // 0x80
	private UIStateFinder m_stateFinder; // 0x88


	// RVA: 0x282fa68 VA: 0x7594e47a68
	public Void ChangeSelect() { }
	// RVA: 0x282fb20 VA: 0x7594e47b20
	public Void Render(Int32 id, Int32 currDayId, Int32 selectedId, MonthlySignInData monthlySignInData, Boolean canTodayCheckin, Boolean playTodayCheckinEffect) { }
	// RVA: 0x282fe2c VA: 0x7594e47e2c
	private IEnumerator _PlayTodayCheckinEffect() { }
	// RVA: 0x282fec8 VA: 0x7594e47ec8
	private Void _ClearEffectIfNot() { }
	// RVA: 0x282ff68 VA: 0x7594e47f68
	private Void OnDisable() { }
	// RVA: 0x282ff6c VA: 0x7594e47f6c
	public Void .ctor() { }
}
```