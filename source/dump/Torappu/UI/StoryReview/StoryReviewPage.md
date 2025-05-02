# StoryReviewPage

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `DataBundle m_initBundle`


## Methods

- `IEnumerator _SetStateViaParam(DataBundle)`

- `Void _OnPageCreated(DataBundle)`

- `IEnumerator _RouteToEntryCoroutine(Boolean)`

- `IEnumerator _JumpToActivityState(DataBundle)`

- `IEnumerator _JumpToMiniState(DataBundle)`

- `String GetStoryBrief(String)`

- `String _GetStoryPath(String)`

- `Boolean CheckIfDataTimeoutAndResync()`

- `PlayerStoryReview GetStoryReviewData()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnReuse(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewPage : StateEnginePage, IHotfixable
{
	private DataBundle m_initBundle; // 0xe8
	private const String STORY_FOLDER; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnReuse; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0__SetStateViaParam; // 0x18
	private static DelegateBridge __Hotfix0__OnPageCreated; // 0x20
	private static DelegateBridge __Hotfix0__RouteToEntryCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__JumpToActivityState; // 0x30
	private static DelegateBridge __Hotfix0__JumpToMiniState; // 0x38
	private static DelegateBridge __Hotfix0_GetStoryBrief; // 0x40
	private static DelegateBridge __Hotfix0__GetStoryPath; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfDataTimeoutAndResync; // 0x50
	private static DelegateBridge __Hotfix0_GetStoryReviewData; // 0x58
	private static DelegateBridge __Hotfix0_LoadStoryReviewEntryImage; // 0x60
	private static DelegateBridge __Hotfix0_LoadMiniActTrialTitleSprite; // 0x68
	private static DelegateBridge __Hotfix0__LoadAutoPackSprite; // 0x70
	private static DelegateBridge __Hotfix0_LoadMiniStoryImage; // 0x78
	private static DelegateBridge __Hotfix0_LoadMiniStoryCharImage; // 0x80
	private static DelegateBridge __Hotfix0_SendStoryReviewUnlock; // 0x88
	private static DelegateBridge __Hotfix0_SendStoryReviewRead; // 0x90
	private static DelegateBridge __Hotfix0_SendRewardGain; // 0x98
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0xa0
	private static DelegateBridge __Hotfix0_DataBundleToStoryReviewDetail; // 0xa8
	private static DelegateBridge __Hotfix0_StartAVGAndBackToStoryReview; // 0xb0
	private static DelegateBridge __Hotfix0__SceneParamToState; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x27570e8 VA: 0x7594d6f0e8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x27571fc VA: 0x7594d6f1fc
	protected override Void OnReuse(DataBundle savedInstance) { }
	// RVA: 0x275728c VA: 0x7594d6f28c
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2757338 VA: 0x7594d6f338
	private IEnumerator _SetStateViaParam(DataBundle param) { }
	// RVA: 0x2757178 VA: 0x7594d6f178
	private Void _OnPageCreated(DataBundle savedInst) { }
	// RVA: 0x2757408 VA: 0x7594d6f408
	private IEnumerator _RouteToEntryCoroutine(Boolean useFastMode) { }
	// RVA: 0x27574d0 VA: 0x7594d6f4d0
	private IEnumerator _JumpToActivityState(DataBundle param) { }
	// RVA: 0x27575a0 VA: 0x7594d6f5a0
	private IEnumerator _JumpToMiniState(DataBundle param) { }
	// RVA: 0x2757670 VA: 0x7594d6f670
	public String GetStoryBrief(String storyId) { }
	// RVA: 0x27577f4 VA: 0x7594d6f7f4
	private String _GetStoryPath(String key) { }
	// RVA: 0x2756428 VA: 0x7594d6e428
	public Boolean CheckIfDataTimeoutAndResync() { }
	// RVA: 0x27578dc VA: 0x7594d6f8dc
	public PlayerStoryReview GetStoryReviewData() { }
	// RVA: 0x2749c70 VA: 0x7594d61c70
	public static Sprite LoadStoryReviewEntryImage(String storyEntryPicId, StoryReviewType reviewType) { }
	// RVA: 0x2749ed0 VA: 0x7594d61ed0
	public static Sprite LoadMiniActTrialTitleSprite(String actId) { }
	// RVA: 0x2757974 VA: 0x7594d6f974
	private static Sprite _LoadAutoPackSprite(String spriteId, String hubPath) { }
	// RVA: 0x2751388 VA: 0x7594d69388
	public static Sprite LoadMiniStoryImage(String storyPicId) { }
	// RVA: 0x2757ad4 VA: 0x7594d6fad4
	public static Sprite LoadMiniStoryCharImage(String miniStoryPicId) { }
	// RVA: 0x274f100 VA: 0x7594d67100
	public static Void SendStoryReviewUnlock(StoryReviewViewModel viewModel, Action onSucc) { }
	// RVA: 0x274e684 VA: 0x7594d66684
	public static Void SendStoryReviewRead(String storyId, Action onSucc) { }
	// RVA: 0x27505e8 VA: 0x7594d685e8
	public static Void SendRewardGain(StoryReviewChapterViewModel chapter, Action onSucc) { }
	// RVA: 0x2757b44 VA: 0x7594d6fb44
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onSuccess) { }
	// RVA: 0x274eb44 VA: 0x7594d66b44
	public static DataBundle DataBundleToStoryReviewDetail(StoryReviewEntryType entryType, String chapterId, Single scrollPos, Boolean backToStage, Boolean exitOnReview, Boolean exitOnDetail, Boolean miniTrail) { }
	// RVA: 0x274ed48 VA: 0x7594d66d48
	public static Void StartAVGAndBackToStoryReview(StoryData targetStory, DataBundle stateBundle) { }
	// RVA: 0x2757c14 VA: 0x7594d6fc14
	private static UIPageControllerParam _SceneParamToState(DataBundle bundleToState) { }
	// RVA: 0x2758054 VA: 0x7594d70054
	public Void .ctor() { }
	// RVA: 0x27580c4 VA: 0x7594d700c4
	private IEnumerator <>n__0() { }
	// RVA: 0x27580cc VA: 0x7594d700cc
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x27580d4 VA: 0x7594d700d4
	private Void <>xLuaBaseProxy_OnReuse(DataBundle P0) { }
	// RVA: 0x27580dc VA: 0x7594d700dc
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```