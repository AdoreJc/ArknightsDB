# ReaderWriterLockSlim

**Namespace:** `System.Threading`


## Fields

- `Boolean fIsReentrant`

- `Int32 myLock`

- `UInt32 numWriteWaiters`

- `UInt32 numReadWaiters`

- `UInt32 numWriteUpgradeWaiters`

- `UInt32 numUpgradeWaiters`

- `Boolean fNoWaiters`

- `Int32 upgradeLockOwnerId`

- `Int32 writeLockOwnerId`

- `EventWaitHandle writeEvent`

- `EventWaitHandle readEvent`

- `EventWaitHandle upgradeEvent`

- `EventWaitHandle waitUpgradeEvent`

- `Int64 lockID`

- `Boolean fUpgradeThreadHoldingRead`

- `UInt32 owners`

- `Boolean fDisposed`


## Properties

- `Boolean IsReadLockHeld`

- `Boolean IsUpgradeableReadLockHeld`

- `Boolean IsWriteLockHeld`

- `Int32 RecursiveReadCount`

- `Int32 RecursiveUpgradeCount`

- `Int32 RecursiveWriteCount`

- `Int32 WaitingReadCount`

- `Int32 WaitingUpgradeCount`

- `Int32 WaitingWriteCount`


## Methods

- `Void InitializeThreadCounts()`

- `Boolean IsRwHashEntryChanged(ReaderWriterCount)`

- `ReaderWriterCount GetThreadRWCount(Boolean)`

- `Void EnterReadLock()`

- `Boolean TryEnterReadLock(Int32)`

- `Boolean TryEnterReadLock(TimeoutTracker)`

- `Boolean TryEnterReadLockCore(TimeoutTracker)`

- `Void EnterWriteLock()`

- `Boolean TryEnterWriteLock(Int32)`

- `Boolean TryEnterWriteLock(TimeoutTracker)`

- `Boolean TryEnterWriteLockCore(TimeoutTracker)`

- `Void EnterUpgradeableReadLock()`

- `Boolean TryEnterUpgradeableReadLock(Int32)`

- `Boolean TryEnterUpgradeableReadLock(TimeoutTracker)`

- `Boolean TryEnterUpgradeableReadLockCore(TimeoutTracker)`

- `Void ExitReadLock()`

- `Void ExitWriteLock()`

- `Void ExitUpgradeableReadLock()`

- `Void LazyCreateEvent(ref, Boolean)`

- `Boolean WaitOnEvent(EventWaitHandle, ref, TimeoutTracker, Boolean)`

- `Void ExitAndWakeUpAppropriateWaiters()`

- `Void ExitAndWakeUpAppropriateWaitersPreferringWriters()`

- `Void ExitAndWakeUpAppropriateReadWaiters()`

- `Boolean IsWriterAcquired()`

- `Void SetWriterAcquired()`

- `Void ClearWriterAcquired()`

- `Void SetWritersWaiting()`

- `Void ClearWritersWaiting()`

- `Void SetUpgraderWaiting()`

- `Void ClearUpgraderWaiting()`

- `UInt32 GetNumReaders()`

- `Void EnterMyLock()`

- `Void EnterMyLockSpin()`

- `Void ExitMyLock()`

- `Void Dispose()`

- `Void Dispose(Boolean)`

- `Boolean get_IsReadLockHeld()`

- `Boolean get_IsUpgradeableReadLockHeld()`

- `Boolean get_IsWriteLockHeld()`

- `Int32 get_RecursiveReadCount()`

- `Int32 get_RecursiveUpgradeCount()`

- `Int32 get_RecursiveWriteCount()`

- `Int32 get_WaitingReadCount()`

- `Int32 get_WaitingUpgradeCount()`

- `Int32 get_WaitingWriteCount()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Threading
public class ReaderWriterLockSlim : IDisposable
{
	private Boolean fIsReentrant; // 0x10
	private Int32 myLock; // 0x14
	private UInt32 numWriteWaiters; // 0x18
	private UInt32 numReadWaiters; // 0x1c
	private UInt32 numWriteUpgradeWaiters; // 0x20
	private UInt32 numUpgradeWaiters; // 0x24
	private Boolean fNoWaiters; // 0x28
	private Int32 upgradeLockOwnerId; // 0x2c
	private Int32 writeLockOwnerId; // 0x30
	private EventWaitHandle writeEvent; // 0x38
	private EventWaitHandle readEvent; // 0x40
	private EventWaitHandle upgradeEvent; // 0x48
	private EventWaitHandle waitUpgradeEvent; // 0x50
	private static Int64 s_nextLockID; // 0x0
	private Int64 lockID; // 0x58
	private static ReaderWriterCount t_rwc; // 0xffffffffffffffff
	private Boolean fUpgradeThreadHoldingRead; // 0x60
	private UInt32 owners; // 0x64
	private Boolean fDisposed; // 0x68

	public Boolean IsReadLockHeld { get; }
	public Boolean IsUpgradeableReadLockHeld { get; }
	public Boolean IsWriteLockHeld { get; }
	public Int32 RecursiveReadCount { get; }
	public Int32 RecursiveUpgradeCount { get; }
	public Int32 RecursiveWriteCount { get; }
	public Int32 WaitingReadCount { get; }
	public Int32 WaitingUpgradeCount { get; }
	public Int32 WaitingWriteCount { get; }

	// RVA: 0x624e85c VA: 0x759886685c
	private Void InitializeThreadCounts() { }
	// RVA: 0x624e868 VA: 0x7598866868
	public Void .ctor(LockRecursionPolicy recursionPolicy) { }
	// RVA: 0x624e8ec VA: 0x75988668ec
	private static Boolean IsRWEntryEmpty(ReaderWriterCount rwc) { }
	// RVA: 0x624e92c VA: 0x759886692c
	private Boolean IsRwHashEntryChanged(ReaderWriterCount lrwc) { }
	// RVA: 0x624e950 VA: 0x7598866950
	private ReaderWriterCount GetThreadRWCount(Boolean dontAllocate) { }
	// RVA: 0x624ea8c VA: 0x7598866a8c
	public Void EnterReadLock() { }
	// RVA: 0x624ea94 VA: 0x7598866a94
	public Boolean TryEnterReadLock(Int32 millisecondsTimeout) { }
	// RVA: 0x624eb48 VA: 0x7598866b48
	private Boolean TryEnterReadLock(TimeoutTracker timeout) { }
	// RVA: 0x624eb4c VA: 0x7598866b4c
	private Boolean TryEnterReadLockCore(TimeoutTracker timeout) { }
	// RVA: 0x624f58c VA: 0x759886758c
	public Void EnterWriteLock() { }
	// RVA: 0x624f594 VA: 0x7598867594
	public Boolean TryEnterWriteLock(Int32 millisecondsTimeout) { }
	// RVA: 0x624f5c0 VA: 0x75988675c0
	private Boolean TryEnterWriteLock(TimeoutTracker timeout) { }
	// RVA: 0x624f5c4 VA: 0x75988675c4
	private Boolean TryEnterWriteLockCore(TimeoutTracker timeout) { }
	// RVA: 0x624fc90 VA: 0x7598867c90
	public Void EnterUpgradeableReadLock() { }
	// RVA: 0x624fc98 VA: 0x7598867c98
	public Boolean TryEnterUpgradeableReadLock(Int32 millisecondsTimeout) { }
	// RVA: 0x624fcc4 VA: 0x7598867cc4
	private Boolean TryEnterUpgradeableReadLock(TimeoutTracker timeout) { }
	// RVA: 0x624fcc8 VA: 0x7598867cc8
	private Boolean TryEnterUpgradeableReadLockCore(TimeoutTracker timeout) { }
	// RVA: 0x62501f4 VA: 0x75988681f4
	public Void ExitReadLock() { }
	// RVA: 0x6250394 VA: 0x7598868394
	public Void ExitWriteLock() { }
	// RVA: 0x62505ec VA: 0x75988685ec
	public Void ExitUpgradeableReadLock() { }
	// RVA: 0x624f35c VA: 0x759886735c
	private Void LazyCreateEvent(ref EventWaitHandle waitEvent, Boolean makeAutoResetEvent) { }
	// RVA: 0x624f464 VA: 0x7598867464
	private Boolean WaitOnEvent(EventWaitHandle waitEvent, ref UInt32 numWaiters, TimeoutTracker timeout, Boolean isWriteWaiter) { }
	// RVA: 0x6250368 VA: 0x7598868368
	private Void ExitAndWakeUpAppropriateWaiters() { }
	// RVA: 0x62507f4 VA: 0x75988687f4
	private Void ExitAndWakeUpAppropriateWaitersPreferringWriters() { }
	// RVA: 0x6250878 VA: 0x7598868878
	private Void ExitAndWakeUpAppropriateReadWaiters() { }
	// RVA: 0x624fc64 VA: 0x7598867c64
	private Boolean IsWriterAcquired() { }
	// RVA: 0x624fc74 VA: 0x7598867c74
	private Void SetWriterAcquired() { }
	// RVA: 0x62505dc VA: 0x75988685dc
	private Void ClearWriterAcquired() { }
	// RVA: 0x625078c VA: 0x759886878c
	private Void SetWritersWaiting() { }
	// RVA: 0x625090c VA: 0x759886890c
	private Void ClearWritersWaiting() { }
	// RVA: 0x625079c VA: 0x759886879c
	private Void SetUpgraderWaiting() { }
	// RVA: 0x625091c VA: 0x759886891c
	private Void ClearUpgraderWaiting() { }
	// RVA: 0x624fc84 VA: 0x7598867c84
	private UInt32 GetNumReaders() { }
	// RVA: 0x625092c VA: 0x759886892c
	private Void EnterMyLock() { }
	// RVA: 0x6250960 VA: 0x7598868960
	private Void EnterMyLockSpin() { }
	// RVA: 0x624f294 VA: 0x7598867294
	private Void ExitMyLock() { }
	// RVA: 0x624f2c4 VA: 0x75988672c4
	private static Void SpinWait(Int32 SpinCount) { }
	// RVA: 0x6250a38 VA: 0x7598868a38
	public Void Dispose() { }
	// RVA: 0x6250a40 VA: 0x7598868a40
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x6250bc8 VA: 0x7598868bc8
	public Boolean get_IsReadLockHeld() { }
	// RVA: 0x6250be0 VA: 0x7598868be0
	public Boolean get_IsUpgradeableReadLockHeld() { }
	// RVA: 0x6250bf8 VA: 0x7598868bf8
	public Boolean get_IsWriteLockHeld() { }
	// RVA: 0x6250c10 VA: 0x7598868c10
	public Int32 get_RecursiveReadCount() { }
	// RVA: 0x6250c90 VA: 0x7598868c90
	public Int32 get_RecursiveUpgradeCount() { }
	// RVA: 0x6250d40 VA: 0x7598868d40
	public Int32 get_RecursiveWriteCount() { }
	// RVA: 0x6250df0 VA: 0x7598868df0
	public Int32 get_WaitingReadCount() { }
	// RVA: 0x6250df8 VA: 0x7598868df8
	public Int32 get_WaitingUpgradeCount() { }
	// RVA: 0x6250e00 VA: 0x7598868e00
	public Int32 get_WaitingWriteCount() { }
}
```