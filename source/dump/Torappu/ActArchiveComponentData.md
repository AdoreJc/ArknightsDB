# ActArchiveComponentData

**Namespace:** `Torappu`


## Fields

- `ActArchiveTimelineData timeline`

- `ActArchiveMusicData music`

- `ActArchivePicData pic`

- `ActArchiveStoryData story`

- `ActArchiveAvgData avg`

- `ActArchiveNewsData news`

- `ActArchiveChallengeBookData challengeBook`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActArchiveComponentData
{
	public ActArchiveTimelineData timeline; // 0x10
	public ActArchiveMusicData music; // 0x18
	public ActArchivePicData pic; // 0x20
	public ActArchiveStoryData story; // 0x28
	public ActArchiveAvgData avg; // 0x30
	public ActArchiveNewsData news; // 0x38
	public Dictionary`2 landmark; // 0x40
	public Dictionary`2 log; // 0x48
	public ActArchiveChallengeBookData challengeBook; // 0x50


	// RVA: 0x34f8764 VA: 0x7595b10764
	public virtual Boolean ShouldSerializetimeline() { }
	// RVA: 0x34f8774 VA: 0x7595b10774
	public virtual Boolean ShouldSerializemusic() { }
	// RVA: 0x34f8784 VA: 0x7595b10784
	public virtual Boolean ShouldSerializepic() { }
	// RVA: 0x34f8794 VA: 0x7595b10794
	public virtual Boolean ShouldSerializestory() { }
	// RVA: 0x34f87a4 VA: 0x7595b107a4
	public virtual Boolean ShouldSerializeavg() { }
	// RVA: 0x34f87b4 VA: 0x7595b107b4
	public virtual Boolean ShouldSerializenews() { }
	// RVA: 0x34f87c4 VA: 0x7595b107c4
	public virtual Boolean ShouldSerializelog() { }
	// RVA: 0x34f87d4 VA: 0x7595b107d4
	public virtual Boolean ShouldSerializelandmark() { }
	// RVA: 0x34f87e4 VA: 0x7595b107e4
	public virtual Boolean ShouldSerializechallengeBook() { }
	// RVA: 0x34f87f4 VA: 0x7595b107f4
	public Void .ctor() { }
}
```