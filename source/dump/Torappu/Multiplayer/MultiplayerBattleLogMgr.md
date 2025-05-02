# MultiplayerBattleLogMgr

**Namespace:** `Torappu.Multiplayer`


## Fields

- `LogItem m_cur`


## Methods

- `Void _SetLogUploaded(String)`

- `Void _DoSave()`

- `Void _TrySaveCurrent()`

- `Int32 _IndexOf(String)`

- `Boolean _NeedUpload(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class MultiplayerBattleLogMgr : Singleton`1
{
	private LogItem m_cur; // 0x10
	private List`1 m_waitForUpload; // 0x30
	private static DelegateBridge __Hotfix0_StartNewBattle; // 0x0
	private static DelegateBridge __Hotfix0_GetLogQueue; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCurrentLogPath; // 0x10
	private static DelegateBridge __Hotfix0_SetCurrentLogNeedToUpload; // 0x18
	private static DelegateBridge __Hotfix0_CheckNeedUpload; // 0x20
	private static DelegateBridge __Hotfix0_get_count; // 0x28
	private static DelegateBridge __Hotfix0_SetLogUploaded; // 0x30
	private static DelegateBridge __Hotfix0_ClearAllLog; // 0x38
	private static DelegateBridge __Hotfix0_get_storageFile; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge __Hotfix0__SetLogUploaded; // 0x50
	private static DelegateBridge __Hotfix0__DoSave; // 0x58
	private static DelegateBridge __Hotfix0__TrySaveCurrent; // 0x60
	private static DelegateBridge __Hotfix0__IndexOf; // 0x68
	private static DelegateBridge __Hotfix0__NeedUpload; // 0x70

	public static Int32 count { get; }
	private static String storageFile { get; }

	// RVA: 0x358879c VA: 0x7595ba079c
	public static Void StartNewBattle() { }
	// RVA: 0x3591d10 VA: 0x7595ba9d10
	public static Void GetLogQueue(Queue`1 queue) { }
	// RVA: 0x3591e48 VA: 0x7595ba9e48
	public static Void UpdateCurrentLogPath(String path) { }
	// RVA: 0x3592084 VA: 0x7595baa084
	public static Void SetCurrentLogNeedToUpload(String remotePath, Boolean toPrivate, String actID) { }
	// RVA: 0x359216c VA: 0x7595baa16c
	public static Boolean CheckNeedUpload() { }
	// RVA: 0x35921d4 VA: 0x7595baa1d4
	public static Int32 get_count() { }
	// RVA: 0x359226c VA: 0x7595baa26c
	public static Void SetLogUploaded(String remotePath) { }
	// RVA: 0x35923c4 VA: 0x7595baa3c4
	public static Void ClearAllLog() { }
	// RVA: 0x35924cc VA: 0x7595baa4cc
	private static String get_storageFile() { }
	// RVA: 0x3592540 VA: 0x7595baa540
	private Void .ctor() { }
	// RVA: 0x35922f8 VA: 0x7595baa2f8
	private Void _SetLogUploaded(String remotePath) { }
	// RVA: 0x3592914 VA: 0x7595baa914
	private Void _DoSave() { }
	// RVA: 0x3591ee8 VA: 0x7595ba9ee8
	private Void _TrySaveCurrent() { }
	// RVA: 0x359281c VA: 0x7595baa81c
	private Int32 _IndexOf(String remotePath) { }
	// RVA: 0x3592bcc VA: 0x7595baabcc
	private Boolean _NeedUpload(String fileName) { }
	// RVA: 0x3592cd0 VA: 0x7595baacd0
	private Void <.ctor>b__14_0(String content) { }
}
```