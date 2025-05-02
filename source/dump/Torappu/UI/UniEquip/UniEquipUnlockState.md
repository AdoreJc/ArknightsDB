# UniEquipUnlockState

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UniEquipUnlockView _unlockView`

- `UniEquipUnlockPreviewView _previewView`

- `Boolean m_isInited`

- `UniEquipUnlockStateBean m_stateBean`


## Methods

- `Void EventOnConfirmClick()`

- `Void _UniqEquipGuideEndCallback(Story)`

- `Void EventOnCancelClick()`

- `Void EventOnClickPreview()`

- `Void _InitIfNot()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipUnlockState : PopupFadeState
{
	private UniEquipUnlockView _unlockView; // 0x70
	private UniEquipUnlockPreviewView _previewView; // 0x78
	private Boolean m_isInited; // 0x80
	private UniEquipUnlockStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmClick; // 0x20
	private static DelegateBridge __Hotfix0__UniqEquipGuideEndCallback; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCancelClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClickPreview; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x22fb888 VA: 0x7594913888
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22fb8f0 VA: 0x75949138f0
	protected override Void OnEnter() { }
	// RVA: 0x22fba44 VA: 0x7594913a44
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x22fbbd8 VA: 0x7594913bd8
	protected override Void OnResume() { }
	// RVA: 0x22fbc74 VA: 0x7594913c74
	public Void EventOnConfirmClick() { }
	// RVA: 0x22fbf44 VA: 0x7594913f44
	private Void _UniqEquipGuideEndCallback(Story story) { }
	// RVA: 0x22fc024 VA: 0x7594914024
	public Void EventOnCancelClick() { }
	// RVA: 0x22fc098 VA: 0x7594914098
	public Void EventOnClickPreview() { }
	// RVA: 0x22fb964 VA: 0x7594913964
	private Void _InitIfNot() { }
	// RVA: 0x22fc18c VA: 0x759491418c
	public Void .ctor() { }
	// RVA: 0x22fc23c VA: 0x759491423c
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x22fc264 VA: 0x7594914264
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22fc26c VA: 0x759491426c
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x22fc294 VA: 0x7594914294
	private Void <>xLuaBaseProxy_OnResume() { }
}
```