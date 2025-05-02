# RecruitGachaPoolDetailHolder

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Transform _container`

- `RecruitAvailDetailView _availObj`

- `RecruitUpDetailView _upObj`

- `RecruitAvailDetailPickUpPart _pickUpObj`

- `RecruitAttainDetailView _attainObj`

- `RecruitFesClassicCharPart _fesClassicCharObj`

- `RecruitSpecialCharPortView _specialCharView`

- `RecruitRateUp6DetailView _rateUp6ViewPrefab`

- `RectTransform _content`

- `ScrollRect _scrollRect`

- `UILayoutDimensionListener m_dimensionListener`


## Methods

- `Void CleanView()`

- `Void RenderGachaDetail(GachaDetailData, Boolean, RarityRank, GachaDetailExtraInput)`

- `Void RenderGachaDetail(String, GachaDetailData, Boolean, Boolean, RarityRank, GachaDetailExtraInput)`

- `Void _InjectPluginsAtHeader(String, GachaDetailData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaPoolDetailHolder : MonoBehaviour, IHotfixable
{
	private const Single SCROLL_TIME; // 0x0
	private Transform _container; // 0x18
	private List`1 _textObjList; // 0x20
	private RecruitAvailDetailView _availObj; // 0x28
	private RecruitUpDetailView _upObj; // 0x30
	private RecruitAvailDetailPickUpPart _pickUpObj; // 0x38
	private RecruitAttainDetailView _attainObj; // 0x40
	private List`1 _imageObjList; // 0x48
	private RecruitFesClassicCharPart _fesClassicCharObj; // 0x50
	private RecruitSpecialCharPortView _specialCharView; // 0x58
	private RecruitRateUp6DetailView _rateUp6ViewPrefab; // 0x60
	private RectTransform _content; // 0x68
	private ScrollRect _scrollRect; // 0x70
	private UILayoutDimensionListener m_dimensionListener; // 0x78
	private static DelegateBridge __Hotfix0_CleanView; // 0x0
	private static DelegateBridge __Hotfix0_RenderGachaDetail; // 0x8
	private static DelegateBridge __Hotfix1_RenderGachaDetail; // 0x10
	private static DelegateBridge __Hotfix0_GetImageTypeResPath; // 0x18
	private static DelegateBridge __Hotfix0_GetRecruit6StarShowFlag; // 0x20
	private static DelegateBridge __Hotfix0__InjectPluginsAtHeader; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x271f8c4 VA: 0x7594d378c4
	public Void CleanView() { }
	// RVA: 0x271f998 VA: 0x7594d37998
	public Void RenderGachaDetail(GachaDetailData detailInfo, Boolean hasSecurity, RarityRank securityRank, GachaDetailExtraInput extraInput) { }
	// RVA: 0x271fa94 VA: 0x7594d37a94
	public Void RenderGachaDetail(String poolId, GachaDetailData detailInfo, Boolean hasRateUp, Boolean hasSecurity, RarityRank securityRank, GachaDetailExtraInput extraInput) { }
	// RVA: 0x2720578 VA: 0x7594d38578
	public static String GetImageTypeResPath(GachaImageType imageType) { }
	// RVA: 0x2720610 VA: 0x7594d38610
	public static Boolean GetRecruit6StarShowFlag(String recruit6StarHint, RarityRank rarityRank) { }
	// RVA: 0x27203e8 VA: 0x7594d383e8
	private Void _InjectPluginsAtHeader(String poolId, GachaDetailData detailInfo) { }
	// RVA: 0x27206a4 VA: 0x7594d386a4
	public Void .ctor() { }
}
```