# HandBookV2GroupMapStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2GroupProperty _property`


## Methods

- `Void ClearViewModel()`

- `String GetMainForceId()`

- `Void InitViewModel(UIPage, String, Boolean)`

- `Void InitViewModelByGroupId(UIPage, String, String, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2GroupMapStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private HandBookV2GroupProperty _property; // 0x18
	private static DelegateBridge __Hotfix0_ClearViewModel; // 0x0
	private static DelegateBridge __Hotfix0_GetMainForceId; // 0x8
	private static DelegateBridge __Hotfix0__GetMainGroup; // 0x10
	private static DelegateBridge __Hotfix0_InitViewModel; // 0x18
	private static DelegateBridge __Hotfix0_CheckConnectList; // 0x20
	private static DelegateBridge __Hotfix0_InitViewModelByGroupId; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2edc590 VA: 0x75954f4590
	public Void ClearViewModel() { }
	// RVA: 0x2edc640 VA: 0x75954f4640
	public String GetMainForceId() { }
	// RVA: 0x2edc6d0 VA: 0x75954f46d0
	private static String _GetMainGroup(HandBookV2GroupViewModel viewModel) { }
	// RVA: 0x2edc890 VA: 0x75954f4890
	public Void InitViewModel(UIPage page, String forceId, Boolean isFromStack) { }
	// RVA: 0x2eddc78 VA: 0x75954f5c78
	public List`1 CheckConnectList(List`1 charList, List`1 connectList) { }
	// RVA: 0x2edca80 VA: 0x75954f4a80
	public Void InitViewModelByGroupId(UIPage page, String groupId, String forceId, String focusCharId, Boolean isFromStack) { }
	// RVA: 0x2ede050 VA: 0x75954f6050
	public Void .ctor() { }
}
```