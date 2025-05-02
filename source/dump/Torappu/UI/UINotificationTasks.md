# UINotificationTasks

**Namespace:** `Torappu.UI`


## Fields

- `String m_uid`


## Methods

- `Void UINotifications_Tick()`

- `TTask _EnsureTask()`

- `Boolean _ResetIfUserChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UINotificationTasks : Singleton`1
{
	private ListDict`2 m_activeTasks; // 0x10
	private String m_uid; // 0x18
	private static DelegateBridge __Hotfix0_RequestTask; // 0x0
	private static DelegateBridge __Hotfix0_RequireMainUITask; // 0x8
	private static DelegateBridge __Hotfix0_UINotifications_Tick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0__EnsureTask; // 0x20
	private static DelegateBridge __Hotfix0__ResetIfUserChanged; // 0x28


	// RVA: 0x VA: 0x0
	public static TTask RequestTask() { }
	// RVA: 0x227555c VA: 0x759488d55c
	public static DefaultMainUITask RequireMainUITask() { }
	// RVA: 0x22744ac VA: 0x759488c4ac
	public Void UINotifications_Tick() { }
	// RVA: 0x22756dc VA: 0x759488d6dc
	private Void .ctor() { }
	// RVA: 0x VA: 0x0
	private TTask _EnsureTask() { }
	// RVA: 0x22755f4 VA: 0x759488d5f4
	private Boolean _ResetIfUserChanged() { }
}
```