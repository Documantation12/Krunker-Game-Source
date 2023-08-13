

---

# Messing Around With Game Source Lol Dont mind me 



## Instructions

1. **Access Krunker and Open DevTools**
   - Launch your preferred web browser.
   - Navigate to [Krunker](https://krunker.io/).
   - Open the browser's developer tools (usually by pressing `F12` or right-clicking and selecting "Inspect").

2. **Refresh the Page and Navigate to Network Tab**
   - Refresh the Krunker page.
   - In the developer tools, click on the "Network" tab.

3. **Find the "seek-game" Request**
   - Look for a request named "seek-game?hostname=krunker.io..." in the network requests list.
   - Click on the request.

4. **Access the JavaScript Virtual Machine (VM)**
   - Inside the "seek-game" request details, locate the "Initiator" column.
   - Click on the link under "Initiator." This link corresponds to a JavaScript virtual machine (VM). VMs are assigned numbers for debugging purposes.

5. **Wait for VM Source to Load**
   - It might take a few minutes (up to 5 minutes) for the VM's source code to load. The time varies depending on your computer's performance.

6. **Save the VM Source Code**
   - Once the VM's source code has loaded, right-click on the tab that displays the source code (usually named "VM XXX:X").
   - Choose "Save as..." to save the source code as a file.
   - Enter a suitable name for the file, ensuring it ends with the `.js` extension (e.g., `krunker.js`).

7. **Close DevTools and Krunker**
   - Close the developer tools tab.
   - You can also close the Krunker tab if you're done with your analysis.

---
