# AutoChessCoinCntPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _textCoinCnt`

- `Text _textCoinCntShadow`

- `Image _imageCoin`

- `Image _imageCoinShadow`

- `UIFollower _follower`

- `Vector2 _offset`

- `CoinSetting _zeroSetting`

- `CoinSetting _normalSetting`

- `UIAnimationLocation _animationLocation`

- `Tween m_tween`

- `Int32 m_targetCoinCnt`

- `Int32 m_currentCoinCnt`

- `CoinSetting m_applyedSetting`


## Properties

- `AutoChessGameMode gameMode`


## Methods

- `AutoChessGameMode get_gameMode()`

- `Void Init(Tile)`

- `Void _TrySetCoinCnt(Object)`

- `Void _OnTargetMoneyGTCurrentMoney()`

- `Void _Hide(Object)`

- `Void _Show(Object)`

- `Void _ApplySetting(CoinSetting)`

- `Int32 <_TrySetCoinCnt>b__19_0()`

- `Void <_TrySetCoinCnt>b__19_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessCoinCntPanel : MonoBehaviour, IHotfixable
{
	private const Single TWEEN_DURATION; // 0x0
	private Text _textCoinCnt; // 0x18
	private Text _textCoinCntShadow; // 0x20
	private Image _imageCoin; // 0x28
	private Image _imageCoinShadow; // 0x30
	private Image[] _coinBgImg; // 0x38
	private UIFollower _follower; // 0x40
	private Vector2 _offset; // 0x48
	private CoinSetting _zeroSetting; // 0x50
	private CoinSetting _normalSetting; // 0x58
	private UIAnimationLocation _animationLocation; // 0x60
	private Tween m_tween; // 0x70
	private Int32 m_targetCoinCnt; // 0x78
	private Int32 m_currentCoinCnt; // 0x7c
	private CoinSetting m_applyedSetting; // 0x80
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__TrySetCoinCnt; // 0x10
	private static DelegateBridge __Hotfix0__OnTargetMoneyGTCurrentMoney; // 0x18
	private static DelegateBridge __Hotfix0__Hide; // 0x20
	private static DelegateBridge __Hotfix0__Show; // 0x28
	private static DelegateBridge __Hotfix0__ApplySetting; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private AutoChessGameMode gameMode { get; }

	// RVA: 0x20688c0 VA: 0x75946808c0
	private AutoChessGameMode get_gameMode() { }
	// RVA: 0x206894c VA: 0x759468094c
	public Void Init(Tile tile) { }
	// RVA: 0x2068c30 VA: 0x7594680c30
	private Void _TrySetCoinCnt(Object arg) { }
	// RVA: 0x2068e78 VA: 0x7594680e78
	private Void _OnTargetMoneyGTCurrentMoney() { }
	// RVA: 0x2068fa8 VA: 0x7594680fa8
	private Void _Hide(Object arg) { }
	// RVA: 0x2069044 VA: 0x7594681044
	private Void _Show(Object arg) { }
	// RVA: 0x206918c VA: 0x759468118c
	private Void _ApplySetting(CoinSetting setting) { }
	// RVA: 0x206931c VA: 0x759468131c
	public Void .ctor() { }
	// RVA: 0x206938c VA: 0x759468138c
	private Int32 <_TrySetCoinCnt>b__19_0() { }
	// RVA: 0x2069394 VA: 0x7594681394
	private Void <_TrySetCoinCnt>b__19_1(Int32 val) { }
}
```