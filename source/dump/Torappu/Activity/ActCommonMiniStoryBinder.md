# ActCommonMiniStoryBinder

**Namespace:** `Torappu.Activity`


## Fields

- `SimpleLayoutContent _viewContainer`

- `ActCommonMiniStoryAdapter m_storyAdapter`

- `AdapterPluginInfo m_adapterPluginInfo`


## Methods

- `Void _UpdateAdapterStatus(ActCommonMiniStoryViewModel)`

- `Void SetCallbacks(Action`1, Action`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonMiniStoryBinder : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _viewContainer; // 0x20
	private ActCommonMiniStoryAdapter m_storyAdapter; // 0x28
	private Action`1 m_onReviewStoryClicked; // 0x30
	private Action`1 m_onStoryUnlockClicked; // 0x38
	private Action`1 m_onStoryReadClicked; // 0x40
	private AdapterPluginInfo m_adapterPluginInfo; // 0x48
	private static DelegateBridge __Hotfix0__UpdateAdapterStatus; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30c936c VA: 0x75956e136c
	private Void _UpdateAdapterStatus(ActCommonMiniStoryViewModel groupModel) { }
	// RVA: 0x30c9690 VA: 0x75956e1690
	public override Void OnValueChanged(ActCommonMiniStoryProperty property) { }
	// RVA: 0x30c985c VA: 0x75956e185c
	public Void SetCallbacks(Action`1 onReviewStoryClicked, Action`1 onUnlockStoryClicked, Action`1 onStoryRead) { }
	// RVA: 0x30c991c VA: 0x75956e191c
	public Void .ctor() { }
}
```