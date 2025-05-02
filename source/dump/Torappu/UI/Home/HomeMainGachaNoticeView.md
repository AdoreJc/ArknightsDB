# HomeMainGachaNoticeView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Transform _noticeContainer`

- `GachaFreeOnceNoticeView _gachaFreeOnceNoticeView`

- `GachaFreeRecruitNoticeView _gachaFreeRecruitNoticeView`

- `GachaFreeOnceNoticeView m_gachaFreeOnceNoticeView`

- `GachaFreeRecruitNoticeView m_gachaFreeRecruitNoticeView`

- `Boolean m_hasInited`


## Methods

- `Void RefreshState()`

- `Void _InitIfNot()`

- `Void _InactivateNoticeViews()`

- `Boolean _CheckAndRenderFreeRecruit(List`1, PlayerGacha)`

- `Boolean _CheckAndRenderFreeOnce(List`1, PlayerGacha)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMainGachaNoticeView : MonoBehaviour, IHotfixable
{
	private Transform _noticeContainer; // 0x18
	private GachaFreeOnceNoticeView _gachaFreeOnceNoticeView; // 0x20
	private GachaFreeRecruitNoticeView _gachaFreeRecruitNoticeView; // 0x28
	private GachaFreeOnceNoticeView m_gachaFreeOnceNoticeView; // 0x30
	private GachaFreeRecruitNoticeView m_gachaFreeRecruitNoticeView; // 0x38
	private Boolean m_hasInited; // 0x40
	private static DelegateBridge __Hotfix0_RefreshState; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__InactivateNoticeViews; // 0x10
	private static DelegateBridge __Hotfix0__CheckAndRenderFreeRecruit; // 0x18
	private static DelegateBridge __Hotfix0__CheckAndRenderFreeOnce; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x283b5e4 VA: 0x7594e535e4
	public Void RefreshState() { }
	// RVA: 0x283b6e4 VA: 0x7594e536e4
	private Void _InitIfNot() { }
	// RVA: 0x283b800 VA: 0x7594e53800
	private Void _InactivateNoticeViews() { }
	// RVA: 0x283b89c VA: 0x7594e5389c
	private Boolean _CheckAndRenderFreeRecruit(List`1 clientPool, PlayerGacha playerGacha) { }
	// RVA: 0x283ba60 VA: 0x7594e53a60
	private Boolean _CheckAndRenderFreeOnce(List`1 clientPool, PlayerGacha playerGacha) { }
	// RVA: 0x283bce4 VA: 0x7594e53ce4
	public Void .ctor() { }
}
```