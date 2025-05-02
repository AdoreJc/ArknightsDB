# UIBattleLoading

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single _fadeTime`

- `Single _loadingDotTime`

- `Text _loadingLabel`

- `Image _backgroundImage`

- `Image _backgroundCover`

- `UIStageInfo _stageInfo`

- `UITipsHolderForBattle _tipsHolder`

- `RectTransform _decorContainer`

- `GameObject _panelOriginDecors`

- `Single m_accumTime`

- `UIBattleLoadingDecor m_decor`

- `DirectAssetLoader m_assetLoader`


## Methods

- `Void SetData(BattleStageInfo)`

- `UIBattleLoadingDecor _LoadLoadingDecor(String)`

- `Single StartSwitchScene()`

- `Void Update()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleLoading : MonoBehaviour, IHotfixable
{
	private const String DEFAULT_LOADING_PIC; // 0x0
	private const Int32 DOT_CNT; // 0x0
	private Single _fadeTime; // 0x18
	private Single _loadingDotTime; // 0x1c
	private Text _loadingLabel; // 0x20
	private Image _backgroundImage; // 0x28
	private Image _backgroundCover; // 0x30
	private UIStageInfo _stageInfo; // 0x38
	private UITipsHolderForBattle _tipsHolder; // 0x40
	private RectTransform _decorContainer; // 0x48
	private GameObject _panelOriginDecors; // 0x50
	private Single m_accumTime; // 0x58
	private UIBattleLoadingDecor m_decor; // 0x60
	private DirectAssetLoader m_assetLoader; // 0x68
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0__LoadLoadingDecor; // 0x8
	private static DelegateBridge __Hotfix0_StartSwitchScene; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2040598 VA: 0x7594658598
	public Void SetData(BattleStageInfo stageInfo) { }
	// RVA: 0x20408c0 VA: 0x75946588c0
	private UIBattleLoadingDecor _LoadLoadingDecor(String loadingPicId) { }
	// RVA: 0x2040fd4 VA: 0x7594658fd4
	public Single StartSwitchScene() { }
	// RVA: 0x2041150 VA: 0x7594659150
	private Void Update() { }
	// RVA: 0x204130c VA: 0x759465930c
	private Void OnDestroy() { }
	// RVA: 0x2041384 VA: 0x7594659384
	public Void .ctor() { }
}
```