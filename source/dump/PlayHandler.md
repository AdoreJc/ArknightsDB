# PlayHandler

**Namespace:** ` `


## Fields

- `UIChatBoxView m_closure`

- `Single m_scrollDur`

- `Boolean <isPlaying>k__BackingField`

- `IVirtualView <tickingItem>k__BackingField`


## Properties

- `Boolean isPlaying`

- `IVirtualView tickingItem`


## Methods

- `Boolean get_isPlaying()`

- `Void set_isPlaying(Boolean)`

- `IVirtualView get_tickingItem()`

- `Void set_tickingItem(IVirtualView)`

- `Boolean _IsValid()`

- `IEnumerator PlayItem(IVirtualView)`

- `IEnumerator PlayItemAndRemove(IVirtualView)`

- `IEnumerator ScrollToBottomIfNecessary()`

- `IEnumerator _PlayItemImpl(IVirtualView)`

- `IEnumerator _ScrollToBottomIfNecessaryImpl()`

- `Void <_PlayItemImpl>b__16_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayHandler : IHotfixable
{
	private const Single DEFAULT_SCROLL_DUR; // 0x0
	private UIChatBoxView m_closure; // 0x10
	private Single m_scrollDur; // 0x18
	private Boolean <isPlaying>k__BackingField; // 0x1c
	private IVirtualView <tickingItem>k__BackingField; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x8
	private static DelegateBridge __Hotfix0_set_isPlaying; // 0x10
	private static DelegateBridge __Hotfix0_get_tickingItem; // 0x18
	private static DelegateBridge __Hotfix0_set_tickingItem; // 0x20
	private static DelegateBridge __Hotfix0__IsValid; // 0x28
	private static DelegateBridge __Hotfix0_PlayItem; // 0x30
	private static DelegateBridge __Hotfix0_PlayItemAndRemove; // 0x38
	private static DelegateBridge __Hotfix0_ScrollToBottomIfNecessary; // 0x40
	private static DelegateBridge __Hotfix0__PlayItemImpl; // 0x48
	private static DelegateBridge __Hotfix0__ScrollToBottomIfNecessaryImpl; // 0x50

	public Boolean isPlaying { get; set; }
	public IVirtualView tickingItem { get; set; }

	// RVA: 0x2c41d64 VA: 0x7595259d64
	public Void .ctor(UIChatBoxView closure, PlayOptions options) { }
	// RVA: 0x2c42b50 VA: 0x759525ab50
	public Boolean get_isPlaying() { }
	// RVA: 0x2c42bb8 VA: 0x759525abb8
	private Void set_isPlaying(Boolean value) { }
	// RVA: 0x2c425ac VA: 0x759525a5ac
	public IVirtualView get_tickingItem() { }
	// RVA: 0x2c42c38 VA: 0x759525ac38
	private Void set_tickingItem(IVirtualView value) { }
	// RVA: 0x2c42cbc VA: 0x759525acbc
	private Boolean _IsValid() { }
	// RVA: 0x2c42d7c VA: 0x759525ad7c
	public IEnumerator PlayItem(IVirtualView view) { }
	// RVA: 0x2c42e74 VA: 0x759525ae74
	public IEnumerator PlayItemAndRemove(IVirtualView view) { }
	// RVA: 0x2c42f6c VA: 0x759525af6c
	public IEnumerator ScrollToBottomIfNecessary() { }
	// RVA: 0x2c43040 VA: 0x759525b040
	private IEnumerator _PlayItemImpl(IVirtualView view) { }
	// RVA: 0x2c43138 VA: 0x759525b138
	private IEnumerator _ScrollToBottomIfNecessaryImpl() { }
	// RVA: 0x2c4320c VA: 0x759525b20c
	private Void <_PlayItemImpl>b__16_0() { }
}
```