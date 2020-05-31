# MySQL_pattern
create pattern in MySQL server

-------------------------------------------------------------------------------------
Declare @variable_name DATATYPE     -- first declare all the
                                    -- variables with datatype
                                    -- like (int)

select @variable = WITH_ANY_VALUE   -- select the variable and 
                                    -- initialize with value

while CONDITION                     -- condition like @variable > 0 

begin                               -- begin

print replicate('*', @variable)     -- replicate insert the *
                                    -- character in variable times

set increment/decrement             -- in increment/decrement
                                    -- @variable= @variable+1
END                                 -- end while loop

-------------------------------------------------------------------------------------


DECLARE @var_name int               -- Declare
DECLARE @var_str VARCHAR(1)         -- Declare
SELECT @var_name = 1                -- initialization
SELECT @var_str = '* '              -- initialization  
WHILE @var_name <= 5                -- Condition 
  BEGIN                             -- Begin 
  PRINT replicate('* ', @var_name)  -- Print 
  SET @var_name = @var_name + 1     -- Set 
  END                               -- end 
