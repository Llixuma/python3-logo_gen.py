# python3-logo_gen.py
A port of the semi lost qcom logo_gen.py to python3

## The script currently generates a 10MiB splash.img, if your original splash.img is bigger or smaller, you need to adjust the following part accordingly:
``` python
    # Calculate the remaining size to fill with zeros
    total_size = 10 * 1024 * 1024  # 10 MiB
    written_size = len(header) + len(body)
    remaining_size = total_size - written_size
```  
  
If you encounter any bugs or have suggestions on how to improve the script, please contribute by opening a merge request with the needed changes.  
  

## this is a WIP, by using this script, you agree to this part of the Licence:
```
# THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESS OR IMPLIED
# WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
# MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT
# ARE DISCLAIMED.  IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS
# BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
# CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
# SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
# BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
# WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE
# OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN
# IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
