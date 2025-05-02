# AudioVolumeTweenBlender

**Namespace:** `Torappu.Audio`


## Methods

- `Single GetValue()`

- `Void AddBlenderItem(String, AudioChannelEffect)`

- `Void RefreshItems()`

- `Boolean IsActive()`

- `Void RemoveBlenderItem(AudioChannelEffect)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioVolumeTweenBlender : IAudioTweenValueBlender, IHotfixable
{
	private Dictionary`2 m_activeBlenderItems; // 0x10
	private List`1 m_pendingRemoveKeys; // 0x18
	private static DelegateBridge __Hotfix0_GetValue; // 0x0
	private static DelegateBridge __Hotfix0_AddBlenderItem; // 0x8
	private static DelegateBridge __Hotfix0_RefreshItems; // 0x10
	private static DelegateBridge __Hotfix0_IsActive; // 0x18
	private static DelegateBridge __Hotfix0_RemoveBlenderItem; // 0x20
	private static DelegateBridge __Hotfix0_Clear; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3eb4744 VA: 0x75964cc744
	public Single GetValue() { }
	// RVA: 0x3eb4c44 VA: 0x75964ccc44
	public Void AddBlenderItem(String channelName, AudioChannelEffect channelEffect) { }
	// RVA: 0x3eb4374 VA: 0x75964cc374
	public Void RefreshItems() { }
	// RVA: 0x3eb8e9c VA: 0x75964d0e9c
	public Boolean IsActive() { }
	// RVA: 0x3eb9054 VA: 0x75964d1054
	public Void RemoveBlenderItem(AudioChannelEffect channelEffect) { }
	// RVA: 0x3eb4b0c VA: 0x75964ccb0c
	public Void Clear() { }
	// RVA: 0x3eb3e6c VA: 0x75964cbe6c
	public Void .ctor() { }
}
```