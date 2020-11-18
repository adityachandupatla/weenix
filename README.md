# Weenix OS
<p>This repository is a placeholder for Weenix Operating System which I, along with two other classmates, have implemented as part of the graduate level course, CSCI 402, which we have taken at USC (Spring 2020). The course instructor was Prof. Bill Cheng.

The goal of the course was to familiarise students with the internals of operating system starting from the abstractions of processes and threads and all the way upto virtual memory.

For more info about the course and instructor, see: http://merlot.usc.edu/william/usc/</p>

<img src="os.png" />

<h2>Project Goals, Concepts, Challenges and Learnings</h2>
<ul>
  <li>Abstraction of threads, processes, and mutex</li>
  <li>Context switching</li>
  <li>Interrupts</li>
  <li>Understanding the boot process of the kernel</li>
  <li>Reference counting in the file system</li>
  <li>System call wrapper</li>
  <li>Case study of S5FS (system V file system)</li>
  <li>Demand paging</li>
  <li>Virtual memory map and the address space representation of a process</li>
  <li>Copy on write mechanism and shadow objects</li>
  <li>
    Memory allocation strategies
    <ul>
      <li>First fit & Best fit (both of which suffer from external fragmentation)</li>
      <li>Buddy system (which is relatively new and chooses internal fragmentation as its design strategy)</li>
      <li>Slab allocation (for pre-defined storage requirements)</li>
    </ul>
  </li>
  <li>Memory layout of a program (text, data, stack and heap sections)</li>
  <li>Write through and write back caches</li>
  <li>Benfits of log structured file system</li>
  <li>File system consistency/fault tolerance: Soft updates vs Shadow paging</li>
  <li>And much more...! (in private repository)</li>
</ul>

<p>Note: The actual repository, which contains the source code, has been made private so as to honour the code of conduct of the University. It will only be available to potential employers who want to assess my capabilities in similar domains (and also who will agree not to share it with anyone else too). If you want to look at the code, email me at: aditya.chandupatla@gmail.com</p>
