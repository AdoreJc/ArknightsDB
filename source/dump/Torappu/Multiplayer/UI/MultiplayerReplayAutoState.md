# MultiplayerReplayAutoState

**Namespace:** `Torappu.Multiplayer.UI`


## Fields

- `InputField _urlInput`


## Methods

- `Void _Play(String[])`

- `Void EventOnPlay()`

- `Void _ParseListFile(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.UI
internal class MultiplayerReplayAutoState : UIPopupState
{
	private InputField _urlInput; // 0x60
	private static DelegateBridge __Hotfix0__Play; // 0x0
	private static DelegateBridge __Hotfix0_EventOnPlay; // 0x8
	private static DelegateBridge __Hotfix0__ParseListFile; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x28
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x30
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3593ad8 VA: 0x7595babad8
	private Void _Play(String[] videoUrls) { }
	// RVA: 0x3593b54 VA: 0x7595babb54
	public Void EventOnPlay() { }
	// RVA: 0x3593d08 VA: 0x7595babd08
	private Void _ParseListFile(String url, String lscontent) { }
	// RVA: 0x3593ffc VA: 0x7595babffc
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x3594174 VA: 0x7595bac174
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x35942ec VA: 0x7595bac2ec
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x35943f8 VA: 0x7595bac3f8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x3594504 VA: 0x7595bac504
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3594568 VA: 0x7595bac568
	public Void .ctor() { }
}
```