  # PDF Compressor (SHRINK)                                                          
  Minimal web app to compress PDFs without losing clarity.                           
  No signup.                                                                         
  No API.                                                                            
  Just clean compression.                                                            
                                                                                     
  ---                                                                                
                                                                                     
  ## Live Demo                                                                       
  https://pdf-compressor-nine.vercel.app/                                            
                                                                                     
  ---                                                                                
                                                                                     
  ## Features                                                                        
  - **Batch compression** – compress multiple PDFs at once                           
  - Drag & drop support                                                              
  - **PDF thumbnails** with visual preview                                           
  - **3 compression presets** (Light, Balanced, Strong)                              
  - **Custom quality slider** (30-100%)                                              
  - **Target size** options (10MB, 5MB, 2MB, 1MB)                                    
  - **Grayscale conversion** for extra compression                                   
  - **Page range** selection (e.g., 1-5, 8, 12-15)                                   
  - **Compression history** stored locally                                           
  - Real-time **progress indicator**                                                 
  - Share via **Web Share API**                                                      
  - Download individual or all files at once                                         
  - No authentication                                                                
  - No ads                                                                           
  - No watermarks                                                                    
                                                                                     
  ---                                                                                
                                                                                     
  ## Tech Stack                                                                      
  - React 19 (Vite)                                                                  
  - PDF.js (PDF rendering)                                                           
  - pdf-lib (PDF manipulation)                                                       
  - Tailwind CSS v4 (Apple-inspired UI)                                              
  - Framer Motion (animations)                                                       
  - Lucide React (icons)                                                             
  - Vercel (static deploy)                                                           
                                                                                     
  ---                                                                                
                                                                                     
  ## How It Works                                                                    
  1. Upload PDFs (or drag & drop multiple files)                                     
  2. Everything is processed fully in the browser                                    
  3. Choose a compression preset or set custom quality                               
  4. Optionally enable grayscale or set target size                                  
  5. Click "Compress" button                                                         
  6. Download your smaller PDFs                                                      
                                                                                     
  > Thumbnails are generated automatically for easy file identification.             
                                                                                     
  ---                                                                                
                                                                                     
  ## Privacy                                                                         
  All processing happens **locally in your browser**.                                
  No PDFs are uploaded to a server.                                                  
  Your files never leave your device.                                                
                                                                                     
  ---                                                                                
                                                                                     
  ## Installation                                                                    
  ```bash                                                                            
  # Clone the repo                                                                   
  git clone https://github.com/berkindev/shrink.git                                  
                                                                                     
  # Install dependencies                                                             
  cd shrink                                                                          
  npm install                                                                        
                                                                                     
  # Run locally                                                                      
  npm run dev                                                                        
                                                                                     
  ---                                                                                
  Limits                                                                             
                                                                                     
  - Maximum 100 MB file size per PDF                                                 
                                                                                     
  ---                                                                                
  Built by https://instagram.com/berkindev as part of 30 Days – 30 Web Apps. 
