+++
title = "Tim Blechmann — C++ Libraries"

[extra]
framed = true
+++

# Tim Blechmann — C++ Libraries

Landing page for my c++ libraries.

---

## Nova Libraries

Personal C++ libraries for systems programming, audio, and real-time applications.

### [nova-symbol](https://github.com/timblechmann/nova_symbol)

Interned, hashed string symbols for C++20. Immutable, flyweight design with pointer-sized storage, fast comparison, and pre-hashed values inspired by Lisp, SmallTalk and SuperCollider.

### [nova-nonnull](https://github.com/timblechmann/nova_nonnull)

Non-null smart pointer adapters and callable wrappers for C++20 with compiler attributes for better code generation. Move-aware wrapper types for unique_ptr, shared_ptr, and function objects.

### [nova-sync](https://github.com/timblechmann/nova_sync)

Synchronization primitives for C++20: specialized mutex and event types optimized for different use cases. Includes spinlocks, fair mutexes, POSIX real-time mutexes, and platform-specific async mutexes (which allow event loop integration).

### [nova-enums](https://github.com/timblechmann/nova_enums)

Smart enums library for C++20 with introspection: string/enum conversions, validity checking, and exhaustive value enumeration via constexpr sorted arrays.

### [nova-memoryresource](https://github.com/timblechmann/nova_memoryresource)

C++ std::pmr::memory_resource implementations. Features real-time-safe TLSF allocator with O(1) guarantees and mimalloc backend support for high-performance memory management.

### [nova-parameter](https://github.com/timblechmann/nova_parameter)

Header-only template keyword parameter library for C++20. Provides type-safe, compile-time parameter extraction, validation concepts, and named template arguments.

### [nova-simd](https://github.com/timblechmann/nova-simd)

Header-only SIMD framework for audio and computer music applications. Provides a templated vec class abstracting SSE/SSE2, AVX, PowerPC/Altivec, and ARM/NEON with vectorized math operations, audio DSP functions, and mixed scalar/vector operations. Originally developed for and extracted from SuperCollider.

---

## Boost Libraries

Contributed libraries in the [Boost C++ Libraries](https://www.boost.org/) collection.

### [Boost.Lockfree](https://www.boost.org/doc/libs/release/doc/html/lockfree.html)

Lock-free FIFO queues and stacks for concurrent programming without mutexes. Broken out of my supernova synthesis server for SuperCollider.

### [Boost.Heap](https://www.boost.org/doc/libs/release/doc/html/heap.html)

Priority queue data structures: d-ary heap, Fibonacci heap, binomial heap, and more. Written for Google's Summer of Code.
