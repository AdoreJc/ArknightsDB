# MiniReviewDetailBinder

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `SimpleLayoutContent _viewContainer`

- `MiniReviewDetailAdapter m_miniReviewAdapter`

- `String m_groupId`

- `AdapterPluginInfo m_adapterPluginInfo`

- `GameObject m_customInfoPrefab`

- `GameObject m_customLockPrefab`

- `UIPageFinder m_finder`


## Methods

- `Void _UpdateAdapterStatus(StoryReviewChapter)`

- `Void SetCallbacks(Action`1, Action`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniReviewDetailBinder : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _viewContainer; // 0x20
	private MiniReviewDetailAdapter m_miniReviewAdapter; // 0x28
	private String m_groupId; // 0x30
	private AdapterPluginInfo m_adapterPluginInfo; // 0x38
	private GameObject m_customInfoPrefab; // 0x50
	private GameObject m_customLockPrefab; // 0x58
	private Action`1 m_onReviewStoryClicked; // 0x60
	private Action`1 m_onUnlockStoryClicked; // 0x68
	private Action`1 m_onStoryRead; // 0x70
	private UIPageFinder m_finder; // 0x78
	private static DelegateBridge __Hotfix0__UpdateAdapterStatus; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x275db80 VA: 0x7594d75b80
	private Void _UpdateAdapterStatus(StoryReviewChapter groupModel) { }
	// RVA: 0x275df0c VA: 0x7594d75f0c
	public override Void OnValueChanged(ActivityReviewDetailProperty property) { }
	// RVA: 0x275e118 VA: 0x7594d76118
	public Void SetCallbacks(Action`1 onReviewStoryClicked, Action`1 onUnlockStoryClicked, Action`1 onStoryRead) { }
	// RVA: 0x275e1d8 VA: 0x7594d761d8
	public Void .ctor() { }
}
```