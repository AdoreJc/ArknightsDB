# UIAnimation

**Namespace:** `Torappu.UI`


## Fields

- `UIAnimationLocation _location`

- `Boolean _isPlayInverse`


## Properties

- `Boolean isPlaying`

- `Single Length`


## Methods

- `Boolean get_isPlaying()`

- `Boolean Play(AnimationOptions)`

- `Void Stop(Boolean)`

- `Void ClipToEnd()`

- `Void ClipToStart()`

- `Single get_Length()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAnimation
{
	private UIAnimationLocation _location; // 0x10
	private Boolean _isPlayInverse; // 0x20

	public Boolean isPlaying { get; }
	public Single Length { get; }

	// RVA: 0x2175bfc VA: 0x759478dbfc
	public Boolean get_isPlaying() { }
	// RVA: 0x2175c44 VA: 0x759478dc44
	public Boolean Play(AnimationOptions option) { }
	// RVA: 0x2175cbc VA: 0x759478dcbc
	public Void Stop(Boolean isTriggerEnd) { }
	// RVA: 0x2175d08 VA: 0x759478dd08
	public Void ClipToEnd() { }
	// RVA: 0x2175d80 VA: 0x759478dd80
	public Void ClipToStart() { }
	// RVA: 0x2175dfc VA: 0x759478ddfc
	public Single get_Length() { }
	// RVA: 0x2175e84 VA: 0x759478de84
	public Void .ctor() { }
}
```