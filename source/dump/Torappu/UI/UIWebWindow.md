# UIWebWindow

**Namespace:** `Torappu.UI`


## Fields

- `Options m_options`

- `Boolean m_isClosing`


## Methods

- `Boolean IsActive()`

- `Void Close()`

- `Void ToastText(Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIWebWindow : IHotfixable
{
	private static Core s_core; // 0x0
	private Options m_options; // 0x10
	private Boolean m_isClosing; // 0x60
	private static DelegateBridge __Hotfix0_HasActiveWindow; // 0x8
	private static DelegateBridge __Hotfix0_OpenWindow; // 0x10
	private static DelegateBridge __Hotfix0_BroadcastHasNewContent; // 0x18
	private static DelegateBridge __Hotfix0_AddMsgReceiver; // 0x20
	private static DelegateBridge __Hotfix0_RemoveMsgReceiver; // 0x28
	private static DelegateBridge __Hotfix0_Preload; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfPreloading; // 0x38
	private static DelegateBridge __Hotfix0_OpenAdditionalMiniWeb; // 0x40
	private static DelegateBridge __Hotfix0_IsAdditionalMiniWebShowing; // 0x48
	private static DelegateBridge __Hotfix0_IsActive; // 0x50
	private static DelegateBridge __Hotfix0_Close; // 0x58
	private static DelegateBridge __Hotfix0_ToastText; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2205210 VA: 0x759481d210
	public static Boolean HasActiveWindow() { }
	// RVA: 0x2205314 VA: 0x759481d314
	public static UIWebWindow OpenWindow(Options options) { }
	// RVA: 0x22055c4 VA: 0x759481d5c4
	public static Void BroadcastHasNewContent(String busType, Boolean updateFromRemote) { }
	// RVA: 0x2205788 VA: 0x759481d788
	public static Void AddMsgReceiver(MsgReceiver receiver) { }
	// RVA: 0x2205854 VA: 0x759481d854
	public static Void RemoveMsgReceiver(MsgReceiver receiver) { }
	// RVA: 0x2204778 VA: 0x759481c778
	public static Void Preload(String busType) { }
	// RVA: 0x22049cc VA: 0x759481c9cc
	public static Boolean CheckIfPreloading() { }
	// RVA: 0x22026c0 VA: 0x759481a6c0
	public static Void OpenAdditionalMiniWeb(MiniWebOptions options) { }
	// RVA: 0x2202264 VA: 0x759481a264
	public static Boolean IsAdditionalMiniWebShowing() { }
	// RVA: 0x2205bac VA: 0x759481dbac
	public Boolean IsActive() { }
	// RVA: 0x2205c50 VA: 0x759481dc50
	public Void Close() { }
	// RVA: 0x2205e0c VA: 0x759481de0c
	public Void ToastText(Int32 level, String message) { }
	// RVA: 0x2205f54 VA: 0x759481df54
	private Void .ctor() { }
	// RVA: 0x2205fd4 VA: 0x759481dfd4
	private static Void .cctor() { }
}
```