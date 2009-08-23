Grid LESS
=========
The LESS Grid System (http://lesscss.org)

To use::

    @import(grid.less);
    
    #wrapper {
        @grid-container;
        
        .header {
            @grid(12);
            
            .logo {
                @grid(3);
                @alpha;
            }
            
            .nav {
                @grid(9);
                @omega;
            }
        }
        
        .content {
            @grid(12);
            
            .main {
                @grid(9);
                @alpha;
            }
            
            .sidebar {
                @grid(3);
                @omega;
            }
        }
        
        .footer {
            @grid(12);
        }
    }